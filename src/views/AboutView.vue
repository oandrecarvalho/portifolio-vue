<template>
  <div
    class="about min-h-screen flex items-center justify-center bg-gradient-to-br from-purple-600 via-indigo-700 to-purple-600 p-4">
    <div
      class="backdrop-blur-lg bg-white/10 border border-white/20 rounded-2xl shadow-xl p-6 max-w-6xl w-full text-white space-y-10">

      <h2 class="text-3xl font-bold text-center">Sobre Mim</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Stack de Desenvolvimento -->
        <div>
          <h3 class="text-xl font-semibold mb-3 border-b border-purple-400 pb-2 text-center">💻 Stack de Desenvolvimento
          </h3>
          <ul class="list-disc list-inside text-left max-w-md mx-auto mb-6">
            <li><span class="text-purple-300 font-medium">HTML</span>, <span
                class="text-purple-300 font-medium">CSS</span>, <span
                class="text-purple-300 font-medium">Tailwind</span>, <span
                class="text-purple-300 font-medium">Bootstrap</span></li>
            <li><span class="text-purple-300 font-medium">JavaScript</span>, <span
                class="text-purple-300 font-medium">Vue.js</span></li>
            <li><span class="text-purple-300 font-medium">C# .NET</span>, <span class="text-purple-300 font-medium">API
                REST</span></li>
            <li><span class="text-purple-300 font-medium">Python</span></li>
            <li><span class="text-purple-300 font-medium">PHP</span></li>
            <li><span class="text-purple-300 font-medium">MySQL</span></li>
            <li><span class="text-purple-300 font-medium">Git</span></li>
            <li><span class="text-purple-300 font-medium">Linux</span></li>
          </ul>

          <div class="flex flex-wrap justify-center gap-4">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" class="h-6"
              alt="JavaScript" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" class="h-6"
              alt="HTML5" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" class="h-6"
              alt="CSS3" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" class="h-6"
              alt="Python" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" class="h-6"
              alt="CSharp" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" class="h-6"
              alt="Bootstrap" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/debian/debian-original.svg" class="h-6"
              alt="Debian" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" class="h-6" alt="Git" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" class="h-6"
              alt="GitHub" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" class="h-6" alt="PHP" />
          </div>
        </div>

        <!-- Soft Skills -->
        <div>
          <h3 class="text-xl font-semibold mb-3 border-b border-purple-400 pb-2 text-center">🧠 Soft Skills</h3>
          <ul class="list-disc list-inside space-y-2">
            <li><span class="text-indigo-300 font-medium">Comunicação Clara</span></li>
            <li><span class="text-indigo-300 font-medium">Trabalho em Equipe</span></li>
            <li><span class="text-indigo-300 font-medium">Resolução de Problemas</span></li>
            <li><span class="text-indigo-300 font-medium">Organização e Proatividade</span></li>
            <li><span class="text-indigo-300 font-medium">Capacidade de Aprendizado Rápido</span></li>
          </ul>
        </div>
      </div>

      <!-- Lista de Projetos -->
      <div>
        <h3 class="text-xl font-semibold mb-3 border-b border-purple-400 pb-2 text-center">🚀 Meus Projetos</h3>
        <ul class="list-disc list-inside space-y-2 text-indigo-200 max-w-2xl">
          <li><a href=""></a> Sistema de FAQ com Vue.js, API C# .NET e Tailwind (Fábrica de Projetos)</li>
          <li><a href="https://github.com/oandrecarvalho/gestao-financas-csharp">App de Finanças Pessoais em C#</a></li>
          <li><a href="https://oandrecarvalho.github.io/pagina-de-login/">Página de Login</a></li>
          <li><a href="https://oandrecarvalho.github.io/api-rick-and-morty/">Consumo da API de Rick and Morty</a></li>
          <li><a href="https://oandrecarvalho.github.io/api-demon-slayer/">Consumo da API de Demon Slayer(Ativar
              extensão de CORS no navegador para visualizar corretamente)</a></li>
          <li><a href="https://github.com/oandrecarvalho/projeto-tailwind">Landing Page com Tailwind sobre trabalho de
              Fábrica de Projetos</a></li>
          <li>Portfólio Pessoal com Vue 3 + Tailwind</li>
        </ul>
      </div>

      <!-- Timeline de Carreira -->
      <div>
        <h3 class="text-xl font-semibold mb-3 border-b border-purple-400 pb-2 text-center">📚 Formação e Carreira</h3>
        <ul class="relative border-l-2 border-indigo-300 pl-6 space-y-6 text-indigo-100">
          <li>
            <div class="text-sm text-indigo-400">2024 - Atualmente</div>
            <div class="font-medium">Universidade de Marília (UNIMAR)</div>
            <div>Curso: Análise e Desenvolvimento de Sistemas</div>
          </li>
          <li>
            <div class="text-sm text-indigo-400">2024</div>
            <div class="font-medium">Analista de Suporte Técnico</div>
            <div>Estagiário de Análise de Suporte Técnico na Toca Imóveis.</div>
          </li>
          <li>
            <div class="text-sm text-indigo-400">2025</div>
            <div class="font-medium">Iniciação Científica em Cybersecurity</div>
            <div>Criação de ambiente de laboratório seguro com Proxmox e Mutillidae</div>
          </li>
        </ul>
      </div>

    </div>
  </div>
</template>