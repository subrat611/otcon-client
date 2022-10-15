<template>
  <nav data-aos="fade-down" class="navbar navbar-expand-lg fixed-top shadow-sm">
    <div class="container">
      <a class="navbar-brand text-dark fw-bold" href="/">OTCON 2.0</a>
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
            <nuxt-link class="nav-link text-dark" to="/">Home</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link text-dark" to="/about">About</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link text-dark" to="/404">Program</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link text-dark" to="/registration"
              >Registration</nuxt-link
            >
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link text-dark" to="/callforpaper"
              >Call for papers</nuxt-link
            >
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link text-dark" to="/committee"
              >Committees</nuxt-link
            >
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link text-dark" to="/keynote"
              >Keynote speaker</nuxt-link
            >
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link text-dark" to="#">Contact us</nuxt-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'ui-navbar',
}
</script>

<style scoped>
.navbar {
  background-color: #ffffff;
}
</style>