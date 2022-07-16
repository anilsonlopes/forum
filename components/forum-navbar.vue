<template>
  <div
    class="bg-white p-5 rounded border container mx-auto sticky top-0 shadow-xl"
  >
    <div class="flex justify-between items-center">
      <div class="font-extrabold text-xl text-red-600">fórum</div>
      <nuxt-link
        to="post/add"
        class="px-10 py-2 rounded-md font-medium bg-red-500 text-white hover:bg-red-600 transition-colors"
      >
        Iniciar discussão
      </nuxt-link>
    </div>
  </div>
</template>
