<template>
  <section class="lTop">
    <MainTitle title="QiitaAPI in Nuxt" />
    <div class="lTop__cover">
      <MainList :lists="lists" />
    </div>
  </section>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      lists: [
        {
          title: 'タイトル01',
        },
        {
          title: 'タイトル02',
        },
        {
          title: 'タイトル03',
        },
        {
          title: 'タイトル04',
        },
      ],
    }
  },
}
</script>

<style lang="scss">
.lTop {
  padding: 30px 20px;
  &__cover {
    border: 1px solid;
    margin-top: 20px;
  }
}
</style>
