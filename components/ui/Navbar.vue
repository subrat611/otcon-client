<template>
  <nav
    :class="{ 'navbar-dark bg-dark': scrollPosition > getWindowHeight() }"
    class="navbar navbar-expand-lg bg-light fixed-top shadow-sm"
  >
    <div class="container">
      <a class="navbar-brand fw-bold" href="/">OTCON 2.0</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/">Home</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/about">About</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/404">Program</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/registration"
              >Registration</nuxt-link
            >
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/callforpaper"
              >Call for papers</nuxt-link
            >
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/committee">Committees</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/keynote"
              >Keynote speaker</nuxt-link
            >
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/contactus">Contact us</nuxt-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'ui-navbar',
  data() {
    return {
      scrollPosition: null,
    }
  },
  methods: {
    updateScroll() {
      this.scrollPosition = window.scrollY
    },
    getWindowHeight() {
      return window.innerHeight
    },
  },
  mounted() {
    window.addEventListener('scroll', this.updateScroll)
  },
}
</script>

<style scoped>
.navbar {
  transition: all 0.5s;
}
</style>
