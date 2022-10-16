<template>
  <page-wrapper>
    <page-header>
      <h2 class="">About</h2>
    </page-header>
    <div class="container">
      <div class="text-center">
        <img
          src="~/assets/images/opjulogo.png"
          alt="logo"
          class="text-center"
        />
      </div>
      <p class="lead">
        OP Jindal University (OPJU) has been established under the aegis of the
        Jindal Education and Welfare Society. The O P Jindal Group is a US$ 22
        billion conglomerate, employing more than 50,000 people with
        manufacturing facilities across India, the US, UK, Australia, Indonesia,
        South Africa, Chile & Mozambique. OPJU is a multidisciplinary university
        aimed at developing young professionals and future leaders who will not
        only power the growth and development of the nation but also become
        responsible citizens of the world. At the core of the university's
        philosophy and approach lies the belief that students learn best when
        exposed to real-world situations and when nurtured through enriching
        interactions with practitioners and professors. Website:
        <a href="">www.opju.ac.in</a>
      </p>
    </div>
  </page-wrapper>
</template>

<script>
import pageHeader from '~/components/page-header.vue'
import PageWrapper from '~/components/page-wrapper.vue'
export default {
  components: { pageHeader, PageWrapper },
  name: 'AboutPage',
}
</script>

<style scoped>
img {
  margin: 2rem 0;
  width: 70px;
  height: auto;
}
</style>