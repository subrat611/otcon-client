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
            <nuxt-link class="nav-link" to="/">
              <span data-bs-toggle="collapse" data-bs-target=".navbar-collapse">
                Home</span
              >
            </nuxt-link>
          </li>
          <!-- <li class="nav-item">
            <nuxt-link class="nav-link" to="/404"
              ><span
                data-bs-toggle="collapse"
                data-bs-target=".navbar-collapse"
              >
                Program</span
              ></nuxt-link
            >
          </li> -->
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/registration"
              ><span
                data-bs-toggle="collapse"
                data-bs-target=".navbar-collapse"
              >
                Registration</span
              ></nuxt-link
            >
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/callforpaper"
              ><span data-bs-toggle="collapse" data-bs-target=".navbar-collapse"
                >Call for papers</span
              ></nuxt-link
            >
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="">
              <div class="dropdown">
                <span data-bs-toggle="dropdown" aria-expanded="false">
                  Committees
                </span>

                <ul class="dropdown-menu">
                  <li>
                    <nuxt-link
                      class="text-dark nav-link dropdown-item px-2"
                      to="/committee"
                    >
                      <span
                        data-bs-toggle="collapse"
                        data-bs-target=".navbar-collapse"
                      >
                        Core-committees
                      </span>
                    </nuxt-link>
                  </li>
                  <li>
                    <nuxt-link
                      to="/"
                      class="text-dark nav-link dropdown-item px-2"
                    >
                      <span
                        data-bs-toggle="collapse"
                        data-bs-target=".navbar-collapse"
                        >IEEE-MP section - core committee</span
                      >
                    </nuxt-link>
                  </li>
                  <li>
                    <nuxt-link
                      to="/"
                      class="text-dark nav-link dropdown-item px-2"
                    >
                      <span
                        data-bs-toggle="collapse"
                        data-bs-target=".navbar-collapse"
                      >
                        OPJU IEEE student chapter
                      </span>
                    </nuxt-link>
                  </li>
                </ul>
              </div>
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/advisoryboard"
              ><span data-bs-toggle="collapse" data-bs-target=".navbar-collapse"
                >Advisory Board</span
              ></nuxt-link
            >
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/keynote"
              ><span data-bs-toggle="collapse" data-bs-target=".navbar-collapse"
                >Keynote speaker</span
              ></nuxt-link
            >
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/contactus"
              ><span data-bs-toggle="collapse" data-bs-target=".navbar-collapse"
                >Contact us</span
              ></nuxt-link
            >
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
  mounted() {
    window.addEventListener('scroll', this.updateScroll)
  },
  methods: {
    updateScroll() {
      this.scrollPosition = window.scrollY
    },
    getWindowHeight() {
      return window.innerHeight
    },
  },
}
</script>

<style scoped>
.navbar {
  transition: all 0.5s;
}
</style>
