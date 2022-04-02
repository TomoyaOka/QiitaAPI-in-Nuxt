<template>
  <ul class="cList">
    <li v-for="(list, index) in lists" :key="index" class="cList__item">
      {{ list.title }}
    </li>
  </ul>
</template>
<script>
export default {
  props: {
    lists: {
      type: Array,
      default: () => [],
    },
  },
}
</script>

<style lang="scss">
.cList {
  display: flex;

  &__item {
    min-width: 200px;
    max-width: 300px;
    padding: 20px;
  }
}
</style>
