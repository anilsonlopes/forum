<template>
  <div
    class="border rounded-md p-5 shadow-sm bg-white hover:bg-gray-50 transition duration-100"
  >
    <div class="flex">
      <div class="flex-1 pr-10">
        <div class="text-2xl font-medium">Nightcrawler</div>
        <div class="text-sm font-medium text-gray-400 mt-1">
          Iniciado por Elliot, 3 dias atrás
        </div>
        <div class="text-gray-500 mt-3">
          A fórmula é correr atrás de crimes e acidentes chocantes, registrar
          tudo e vender a história para veiculos interessados.
        </div>
      </div>
      <div>
        <div class="flex -space-x-2 overflow-hidden">
          <img
            v-for="index in 4"
            :key="index"
            class="inline-block h-6 w-6 rounded-full ring-2 ring-white"
            src="https://images.unsplash.com/photo-1517365830460-955ce3ccd263?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
            alt="Pessoa"
          />
        </div>
        <div class="mt-2 text-gray-400 self-center flex items-center space-x-2">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            width="1em"
            height="1em"
            viewBox="0 0 24 24"
          >
            <path
              fill="currentColor"
              d="M12 2A10 10 0 0 0 2 12a9.89 9.89 0 0 0 2.26 6.33l-2 2a1 1 0 0 0-.21 1.09A1 1 0 0 0 3 22h9a10 10 0 0 0 0-20Zm0 18H5.41l.93-.93a1 1 0 0 0 0-1.41A8 8 0 1 1 12 20Z"
            ></path>
          </svg>
          <span class="text-sm font-medium">25 comentários</span>
        </div>
      </div>
    </div>
  </div>
</template>
