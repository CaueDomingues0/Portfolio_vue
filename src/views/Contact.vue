<template>
  <div class="bg-gray-50">
    <section class="max-w-3xl mx-auto mb-12 pt-6">
      <h1 class="text-2xl font-bold mb-6 text-center text-gray-800">Entre em Contato</h1>
      
      <div class="bg-white rounded shadow p-4 mb-8">
        <p class="text-gray-700 mb-6 text-center">
          Estou disponível para novos projetos e oportunidades. Entre em contato através do formulário abaixo ou pelas minhas redes sociais.
        </p>
        
        <form class="space-y-4">
          <div>
            <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Nome</label>
            <input type="text" id="name" name="name" class="w-full px-3 py-2 border border-gray-300 rounded" placeholder="Seu nome" required>
          </div>
          
          <div>
            <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email</label>
            <input type="email" id="email" name="email" class="w-full px-3 py-2 border border-gray-300 rounded" placeholder="seu.email@exemplo.com" required>
          </div>
          
          <div>
            <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Mensagem</label>
            <textarea id="message" name="message" rows="4" class="w-full px-3 py-2 border border-gray-300 rounded" placeholder="Escreva sua mensagem aqui..." required></textarea>
          </div>
          
          <div>
            <button type="submit" class="w-full bg-gray-700 hover:bg-gray-800 text-white font-medium py-2 px-4 rounded">Enviar Mensagem</button>
          </div>
        </form>
      </div>
      
      <div class="bg-white rounded shadow p-4">
        <h2 class="text-xl font-semibold mb-4 text-center text-gray-800">Redes Sociais</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
          <!-- GitHub -->
          <a href="https://github.com/CaueDomingues0" target="_blank" class="bg-gray-100 p-4 rounded flex items-center">
            <svg class="h-5 w-5 text-gray-700 mr-3" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
              <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd"/>
            </svg>
            <span class="text-gray-700">GitHub</span>
          </a>
          
          <!-- LinkedIn -->
          <a href="#" class="bg-gray-100 p-4 rounded flex items-center">
            <svg class="h-5 w-5 text-gray-700 mr-3" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
              <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.454C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.225 0z"/>
            </svg>
            <span class="text-gray-700">LinkedIn</span>
          </a>
          
          <!-- Email -->
          <a href="mailto:contato@exemplo.com" class="bg-gray-100 p-4 rounded flex items-center">
            <svg class="h-5 w-5 text-gray-700 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
            </svg>
            <span class="text-gray-700">Email</span>
          </a>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
</script>
