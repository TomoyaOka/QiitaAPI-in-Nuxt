<template>
  <h2 class="cMainTitle">{{ title }}</h2>
</template>

<script>
export default {
  props: {
    title: {
      type: String /* タイプの指定 */,
      default: '' /* デフォルトの指定 */,
    },
  },
}
</script>

<style lang="scss">
.cMainTitle {
  font-size: 24px;
  color: #333;
}
</style>
