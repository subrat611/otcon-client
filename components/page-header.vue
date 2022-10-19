<template>
  <div class="page-header">
    <div class="container">
      <slot></slot>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
    },
  },
}
</script>

<style  scoped>
.page-header {
  padding: 3rem;
  height: 100%;
  background-image: linear-gradient(
      to right,
      #1d1b1bcb,
      rgba(36, 38, 39, 0.715)
    ),
    url('https://images.unsplash.com/photo-1477281765962-ef34e8bb0967?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1033&q=80');
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

h2 {
  color: #fff;
}
</style>