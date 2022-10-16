<template>
  <div>
    <UiNavbar />
    <main class="o-main-wrapper">
      <nuxt />
    </main>
    <uiFooter />
  </div>
</template>

<script>
export default {
  name: 'defalultLayout',
}
</script>

<style  scoped>
.o-main-wrapper {
  padding: 0 0 0 0;
}
</style>