<template>
  <div class="p-10 space-y-10">
    <div class="container mx-auto p-5 rounded border shadow-sm bg-white">
      <div class="text-3xl font-medium">
        Best way to export data in xml and csv format
      </div>
      <div class="mt-5 flex items-center space-x-3">
        <div class="w-10 h-10 rounded-full bg-gray-200"></div>
        <div class="text-sm">
          <div class="font-medium">Nightcrawler</div>
          <div class="text-gray-500">4 dias atrás</div>
        </div>
      </div>
      <div class="mt-5 text-gray-700">
        É um facto estabelecido de que um leitor é distraído pelo conteúdo
        legível de uma página quando analisa a sua mancha gráfica. Logo, o uso
        de Lorem Ipsum leva a uma distribuição mais ou menos normal de letras,
        ao contrário do uso de "Conteúdo aqui, conteúdo aqui", tornando-o texto
        legível.
      </div>
    </div>
    <div class="container mx-auto p-5 rounded border shadow-sm bg-white">
      <div class="font-medium border-b pb-5">4 comentários</div>
      <ul class="divide-y">
        <li v-for="i in 4" :key="i" class="py-10">
          <div class="flex items-center space-x-3">
            <div class="w-10 h-10 rounded-full bg-gray-200"></div>
            <div class="text-sm">
              <div class="font-medium">User Name</div>
              <div class="text-gray-500">4 dias atrás</div>
            </div>
          </div>
          <div class="mt-3 text-gray-500">
            Existem muitas variações das passagens do Lorem Ipsum disponíveis,
            mas a maior parte sofreu alterações de alguma forma, pela injecção
            de humor, ou de palavras aleatórias que nem sequer parecem
            suficientemente credíveis.
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  layout: 'forum',
})
</script>
