<template>
    <nav class="navigation bg-purple-800 text-white py-4 px-8 flex justify-between items-center">
        <h1 class="text-2xl font-bold">André Luís</h1>
        <ul class="flex gap-6">
            <li>
                <router-link to="/" class="relative">Início</router-link>
            </li>
            <li>
                <router-link to="/about" class="relative">Sobre</router-link>
            </li>
            <li>
                <router-link to="/contact" class="relative">Contato</router-link>
            </li>
        </ul>
    </nav>
</template>

<style scoped>
.navigation a {
    position: relative;
    display: inline-block;
    padding-bottom: 4px;
}

/* Linha com gradiente animado */
.navigation a::after {
    content: '';
    position: absolute;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 3px;
    background: linear-gradient(90deg, #8a2be2, #0084ff, #8a2be2);
    background-size: 200% 100%;
    border-radius: 4px;
    transform: scaleX(0);
    transform-origin: right;
    transition: transform 0.4s ease-in-out;
    animation: none;
}

/* Hover com transição suave */
.navigation a:hover::after {
    transform: scaleX(1);
    transform-origin: left;
    animation: gradientMove 2s linear infinite;
}

/* Ativo com mesmo efeito */
.navigation a.router-link-exact-active::after {
    transform: scaleX(1);
    transform-origin: left;
    animation: gradientMove 2s linear infinite;
}

/* Keyframes para mover o gradiente */
@keyframes gradientMove {
    0% {
        background-position: 0% 50%;
    }

    100% {
        background-position: 200% 50%;
    }
}
</style>