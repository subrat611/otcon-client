<template>
  <div>
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
      <h1 class="mb-2">Technical Program Committee</h1>
      <table class="table text-center table-bordered mt-3">
        <tbody>
          <tr>
            <td>Chief Patron</td>
            <td>Mr. Naveen Jindal</td>
            <td></td>
          </tr>
          <tr>
            <td>Patron</td>
            <td>Ms. Shallu Jindal</td>
            <td></td>
          </tr>
          <tr>
            <td>Chairman</td>
            <td>Dr. R.D. Patidar</td>
            <td></td>
          </tr>
          <tr>
            <td>Chairman</td>
            <td>Dr. R.D. Patidar</td>
            <td></td>
          </tr>
          <tr>
            <td>Convener</td>
            <td>Dr. Ashok Bhansali</td>
            <td>Dr. Siddharth S Chakrabarti</td>
          </tr>
          <tr>
            <td>Co-Convener</td>
            <td>Dr. Rakesh Nayak</td>
            <td>Dr. Bhupesh Kumar Dewangan</td>
          </tr>
          <tr>
            <td>Organizing Secretaries</td>
            <td>Dr. Nitesh Bharadwaj</td>
            <td>Dr. Deepak Singh</td>
          </tr>
          <tr>
            <td>Joint Secretaries</td>
            <td>Dr. Rajesh Jha</td>
            <td>Dr. Sushree Diptimayee Swain</td>
          </tr>
          <tr>
            <td>Technical Program Chair</td>
            <td>Dr. Saroj Chandra</td>
            <td></td>
          </tr>
          <tr>
            <td>Publication Chair</td>
            <td>Dr. Sandeep Biswal</td>
            <td></td>
          </tr>
          <tr>
            <td>Publicity Chair</td>
            <td>Dr Sanjay Singh</td>
            <td></td>
          </tr>
          <tr>
            <td>Finance Chair</td>
            <td>Mr Siddhant Chaturvedi</td>
            <td></td>
          </tr>
          <tr>
            <td>Web Chair</td>
            <td>Dr. Abhilasha Chaudhary</td>
            <td></td>
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