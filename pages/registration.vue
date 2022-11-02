<template>
  <page-wrapper>
    <page-header>
      <h2 class="">Registration</h2>
    </page-header>
    <div class="container mt-4 py-4">
      <div class="row">
        <div class="col-lg-12 col-sm-12">
          <ui-reg-form-fee />
        </div>
        <div class="col-12 col-lg-4 mt-4">
          <p class="text-dark fw-semibold">
            Account details for conference registration.
          </p>
          <div class="card bg-success">
            <div class="card-body text-light">
              <div>
                <h6 class="card-title d-inline title--color">Account Name:</h6>
                <span>O P JINDAL UNIVERSITY</span>
              </div>
              <div>
                <h6 class="card-title d-inline title--color">
                  Account Number:
                </h6>
                <span>34368061214</span>
              </div>
              <div>
                <h6 class="card-title d-inline title--color">Bank Name:</h6>
                <span>State Bank of India</span>
              </div>
              <div>
                <h6 class="card-title d-inline title--color">Branch Name:</h6>
                <span>GERWANI BRANCH</span>
              </div>
              <div>
                <h6 class="card-title d-inline title--color">IFSC CODE:</h6>
                <span>SBIN0012145</span>
              </div>
            </div>
          </div>
          <div>
            <p class="text-danger py-2">
              Note: 18% GST will be applicable apart from above mentioned
              registration fees.
            </p>
          </div>
        </div>
      </div>
    </div>
  </page-wrapper>
</template>

<script>
export default {
  name: 'RegistrationPage',
}
</script>