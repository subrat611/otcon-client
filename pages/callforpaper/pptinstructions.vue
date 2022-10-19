<template>
  <page-wrapper>
    <page-header>
      <h2 class="">Call For Papers</h2>
      <h5 class="mt-3 text-light">
        2nd OPJU International Conference On Emerging Technologies And
        Sustainable Development
      </h5>
    </page-header>
    <div class="container">
      <div class="row my-2 py-2 bg-light text-sm-center">
        <div class="col-sm-4">
          <nuxt-link class="nav-link" to="callforpapersub"
            >Camera Ready Submission</nuxt-link
          >
        </div>
        <div class="col-sm-auto">
          <nuxt-link class="nav-link" to="pptinstructions"
            >PPT Instructions</nuxt-link
          >
        </div>
      </div>
      <h4 class="mt-5">PPT Instructions</h4>
      <coming-soon />
    </div>
  </page-wrapper>
</template>

<script>
import pageWrapper from '~/components/page-wrapper.vue'
export default {
  components: { pageWrapper },
  name: 'PPTInstructionsPage',
}
</script>