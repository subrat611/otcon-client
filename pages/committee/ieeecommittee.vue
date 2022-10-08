<template>
  <div>
    <ui-navbar></ui-navbar>
    <div class="container">
      <h1 class="mt-4 py-3">Committee</h1>
      <div class="row">
        <div class="col-md-3 border border-black text-md-center p-2">
          <nuxt-link to="/committee" class="nav-link"
            >Organizing Committee</nuxt-link
          >
        </div>
        <div class="col-md-3 border border-black text-md-center p-2">
          <nuxt-link to="techcommitee" class="nav-link"
            >Technical Program Committee</nuxt-link
          >
        </div>
        <div class="col-md-4 border border-black text-md-center p-2">
          <nuxt-link to="ieeecommittee" class="nav-link"
            >IEEE MP Section Oversight Committee (SOC)</nuxt-link
          >
        </div>
      </div>
    </div>
    <div class="container my-4 py-4">
      <h1 class="mb-2">IEEE MP Section Oversight Committee (SOC)</h1>
      <table class="table text-center table-bordered mt-3">
        <thead>
          <tr>
            <th>Name</th>
            <th>Email</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Dr. Vivek Tiwari</td>
            <td>viveknitbpl@gmail.com</td>
          </tr>
          <tr>
            <td>Dr. R N Patel</td>
            <td>rnpatel.ee@nitrr.ac.in</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style scoped>
.nav-link:hover {
  color: #3a86ff;
}
</style>