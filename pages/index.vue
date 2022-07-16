<template>
  <div class="mx-auto mt-20 px-10 container">
    <div>
      <forum-filter />
    </div>
    <div class="mt-5 space-y-10">
      <nuxt-link
        v-for="index in 5"
        :key="index"
        class="block"
        :to="{ name: 'post-id', params: { id: index } }"
      >
        <forum-post />
      </nuxt-link>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
  layout: 'forum',
})
</script>
