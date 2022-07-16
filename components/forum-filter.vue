<template>
  <div class="border rounded-md flex max-w-xs overflow-hidden">
    <button
      v-for="tab in tabs"
      :key="tab"
      type="button"
      class="tab-nav"
      :class="{ 'tab-nav-active': tabActive === tab }"
      @click="tabActive = tab"
    >
      {{ tab }}
    </button>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data: () => ({
    tabActive: 'Novos',
    tabs: ['Antigos', 'Novos', 'Hot'],
  }),
})
</script>

<style lang="postcss" scoped>
.tab-nav {
  @apply w-full p-2 shadow-sm;
}

.tab-nav:first-of-type {
  @apply rounded-l-md;
}

.tab-nav:last-of-type {
  @apply rounded-r-md;
}

.tab-nav-active {
  @apply bg-white;
}

.tab-nav:not(.tab-nav-active) {
  @apply bg-gray-100;
}
</style>
