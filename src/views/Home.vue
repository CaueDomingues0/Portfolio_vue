<template>
  <div class="bg-gray-50">
    <!-- Seção de Apresentação -->
    <section class="mb-12 pt-6">
      <div class="max-w-2xl mx-auto text-center">
        <h1 class="text-3xl font-bold mb-4 text-gray-800">Cauê Domingues</h1>
        <p class="text-lg text-gray-600 mb-6">Analista de suporte com foco em Análise de Dados.</p>
        <div class="flex justify-center space-x-4">
          <a href="#projects" class="bg-gray-700 hover:bg-gray-800 text-white font-medium py-2 px-4 rounded">Ver Projetos</a>
          <a href="/contact" class="bg-gray-200 hover:bg-gray-300 text-gray-800 font-medium py-2 px-4 rounded">Contato</a>
        </div>
      </div>
    </section>

    <section id="projects" class="max-w-4xl mx-auto mb-12 px-4">
      <h2 class="text-2xl font-bold mb-6 text-center text-gray-800">Meus Projetos</h2>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-white rounded shadow p-4">
          <h3 class="text-lg font-semibold mb-2 text-gray-800">Portfolio Pessoal</h3>
          <p class="text-gray-600 mb-3">Portfolio online com foco em apresentar habilidades, experiências, formação e projetos.</p>
          <div class="flex flex-wrap gap-2 mb-3">
            <span class="px-2 py-1 bg-gray-100 text-gray-800 rounded text-xs">HTML5</span>
            <span class="px-2 py-1 bg-gray-100 text-gray-800 rounded text-xs">CSS3</span>
            <span class="px-2 py-1 bg-gray-100 text-gray-800 rounded text-xs">JavaScript</span>
          </div>
          <a href="https://github.com/CaueDomingues0/Cau-_portfolio" target="_blank" class="text-gray-700 hover:text-gray-900 text-sm">Ver no GitHub →</a>
        </div>

        <div class="bg-white rounded shadow p-4">
          <h3 class="text-lg font-semibold mb-2 text-gray-800">Site Especial</h3>
          <p class="text-gray-600 mb-3">Página web dedicada a uma pessoa especial com fotos, vídeo e mensagem interativa.</p>
          <div class="flex flex-wrap gap-2 mb-3">
            <span class="px-2 py-1 bg-gray-100 text-gray-800 rounded text-xs">HTML5</span>
            <span class="px-2 py-1 bg-gray-100 text-gray-800 rounded text-xs">Tailwind CSS</span>
            <span class="px-2 py-1 bg-gray-100 text-gray-800 rounded text-xs">JavaScript</span>
          </div>
          <a href="https://github.com/CaueDomingues0/Site_Namorada" target="_blank" class="text-gray-700 hover:text-gray-900 text-sm">Ver no GitHub →</a>
        </div>

        <div class="bg-white rounded shadow p-4">
          <h3 class="text-lg font-semibold mb-2 text-gray-800">Jogo da Memória Pokémon</h3>
          <p class="text-gray-600 mb-3">Jogo da memória temático de Pokémon usando a PokeAPI para buscar os Pokémon dinamicamente.</p>
          <div class="flex flex-wrap gap-2 mb-3">
            <span class="px-2 py-1 bg-gray-100 text-gray-800 rounded text-xs">HTML5</span>
            <span class="px-2 py-1 bg-gray-100 text-gray-800 rounded text-xs">CSS3</span>
            <span class="px-2 py-1 bg-gray-100 text-gray-800 rounded text-xs">PokeAPI</span>
          </div>
          <a href="https://github.com/CaueDomingues0/Aplica-Front-End-com-API-Externa-Cau-" target="_blank" class="text-gray-700 hover:text-gray-900 text-sm">Ver no GitHub →</a>
        </div>
      </div>
    </section>

    <section class="max-w-2xl mx-auto text-center pb-12 px-4">
      <h2 class="text-2xl font-bold mb-4 text-gray-800">Vamos trabalhar juntos?</h2>
      <p class="text-gray-600 mb-6">Estou sempre aberto a novos desafios e oportunidades de colaboração.</p>
      <a href="/contact" class="inline-block bg-gray-700 hover:bg-gray-800 text-white font-medium py-2 px-4 rounded">Entre em contato</a>
    </section>
  </div>
</template>

<script setup>
</script>
