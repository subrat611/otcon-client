<template>
  <div>
    <ui-navbar></ui-navbar>
    <div class="container position-relative">
      <h1 class="text-center py-5 fw-bolder">About OPJU</h1>
      <p class="py-4 px-5 fs-5">
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
      <img
        src="~/assets/images/opjulogo.png"
        alt="logo"
        style="width: 100px"
        class="position-absolute"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutPage',
}
</script>

<style scoped>
.position-absolute {
  right: 10rem;
}
</style>