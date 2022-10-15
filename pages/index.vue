<template>
  <div>
    <div class="container-fluid px-0">
      <div class="container text-center">
        <div class="row align-items-center hero-content pt-5">
          <div class="col-12">
            <img
              src="../assets/images/ieee.png"
              alt="iee image"
              class="iee-img"
            />
          </div>
          <div class="col-12 mt-5">
            <p class="o-title text-light fw-bolder">OTCON 2.0</p>
          </div>
          <div
            class="
              col-12
              text-light
              d-flex
              justify-content-center
              align-items-center
            "
          >
            <div class="col-2 col-md-1 border rounded me-4 pt-4">
              <h3>{{ days }}</h3>
              <p>days</p>
            </div>
            <div class="me-3"><h2>:</h2></div>
            <div class="col-2 col-md-1 border rounded me-4 pt-4">
              <h3>{{ hours }}</h3>
              <p>hours</p>
            </div>
            <div class="me-3"><h2>:</h2></div>
            <div class="col-2 col-md-1 border rounded me-4 pt-4">
              <h3>{{ mins }}</h3>
              <p>mins</p>
            </div>
            <div class="me-3"><h2>:</h2></div>
            <div class="col-2 col-md-1 border rounded pt-4">
              <h3>{{ sec }}</h3>
              <p>sec</p>
            </div>
          </div>
          <h5 class="text-light text-uppercase fw-bolder mt-3">
            Event Starts In
          </h5>
          <div class="col my-5">
            <p class="text-light">
              OPJU INTERNATIONAL TECHNOLOGY CONFERENCE <br />On Emerging
              Technology for Sustainable Development (8-10 Feb, 2023)
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="container mt-4 py-4">
      <h1 class="text-center py-4">Conference Tracks</h1>
      <div class="row row-cols-3">
        <div class="col">
          <div class="card mb-3 p-2" style="max-width: 440px">
            <div class="row g-0 align-items-center">
              <div class="col-md-auto">
                <img
                  src="https://cdn-icons-png.flaticon.com/64/2821/2821637.png"
                  class="img-fluid rounded-start"
                  alt="img"
                />
              </div>
              <div class="col-md-10">
                <div class="card-body pe-0">
                  <h5 class="card-title">Emerging And Intelligent Computing</h5>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card mb-3 p-2" style="max-width: 440px">
            <div class="row g-0 align-items-center">
              <div class="col-md-auto">
                <img
                  src="https://cdn-icons-png.flaticon.com/64/2821/2821637.png"
                  class="img-fluid rounded-start"
                  alt="img"
                />
              </div>
              <div class="col-md-10">
                <div class="card-body pe-0">
                  <h5 class="card-title">
                    Communication Control And Networking
                  </h5>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card mb-3 p-2" style="max-width: 440px">
            <div class="row g-0 align-items-center">
              <div class="col-md-auto">
                <img
                  src="https://cdn-icons-png.flaticon.com/64/2821/2821637.png"
                  class="img-fluid rounded-start"
                  alt="img"
                />
              </div>
              <div class="col-md-10">
                <div class="card-body pe-0">
                  <h5 class="card-title">Renewable Energy And Power System</h5>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card mb-3 p-2" style="max-width: 440px">
            <div class="row g-0 align-items-center">
              <div class="col-md-auto">
                <img
                  src="https://cdn-icons-png.flaticon.com/64/2821/2821637.png"
                  class="img-fluid rounded-start"
                  alt="img"
                />
              </div>
              <div class="col-md-10">
                <div class="card-body pe-0">
                  <h5 class="card-title">Bio Informatics And Health Care</h5>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card mb-3 p-2" style="max-width: 440px">
            <div class="row g-0 align-items-center">
              <div class="col-md-auto">
                <img
                  src="https://cdn-icons-png.flaticon.com/64/2821/2821637.png"
                  class="img-fluid rounded-start"
                  alt="img"
                />
              </div>
              <div class="col-md-10">
                <div class="card-body pe-0">
                  <h5 class="card-title">IoT Automation And Manufacturing</h5>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card mb-3 p-2" style="max-width: 440px">
            <div class="row g-0 align-items-center">
              <div class="col-md-auto">
                <img
                  src="https://cdn-icons-png.flaticon.com/64/2821/2821637.png"
                  class="img-fluid rounded-start"
                  alt="img"
                />
              </div>
              <div class="col-md-10">
                <div class="card-body pe-0">
                  <h5 class="card-title">Signal And Image Processing</h5>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card mb-3 p-2" style="max-width: 440px">
            <div class="row g-0 align-items-center">
              <div class="col-md-auto">
                <img
                  src="https://cdn-icons-png.flaticon.com/64/2821/2821637.png"
                  class="img-fluid rounded-start"
                  alt="img"
                />
              </div>
              <div class="col-md-10">
                <div class="card-body pe-0">
                  <h5 class="card-title">
                    Cyber Physical System And Metaverse
                  </h5>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card mb-3 p-2" style="max-width: 440px">
            <div class="row g-0 align-items-center">
              <div class="col-md-auto">
                <img
                  src="https://cdn-icons-png.flaticon.com/64/2821/2821637.png"
                  class="img-fluid rounded-start"
                  alt="img"
                />
              </div>
              <div class="col-md-10">
                <div class="card-body pe-0">
                  <h5 class="card-title">
                    Education Environment And Economics
                  </h5>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container mt-4 py-4">
      <h1 class="py-4">Important Dates</h1>
      <div class="accordion" id="accordionExample">
        <div class="accordion-item">
          <h2 class="accordion-header" id="headingOne">
            <button
              class="accordion-button"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#collapseOne"
              aria-expanded="true"
              aria-controls="collapseOne"
            >
              <strong>Paper Submission Due</strong>
            </button>
          </h2>
          <div
            id="collapseOne"
            class="accordion-collapse collapse show"
            aria-labelledby="headingOne"
            data-bs-parent="#accordionExample"
          >
            <div class="accordion-body">30th November 2022</div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="headingTwo">
            <button
              class="accordion-button collapsed"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#collapseTwo"
              aria-expanded="false"
              aria-controls="collapseTwo"
            >
              <strong>Notification of Acceptance</strong>
            </button>
          </h2>
          <div
            id="collapseTwo"
            class="accordion-collapse collapse"
            aria-labelledby="headingTwo"
            data-bs-parent="#accordionExample"
          >
            <div class="accordion-body">15th December 2022</div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="headingThree">
            <button
              class="accordion-button collapsed"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#collapseThree"
              aria-expanded="false"
              aria-controls="collapseThree"
            >
              <strong>Camera Ready Submission</strong>
            </button>
          </h2>
          <div
            id="collapseThree"
            class="accordion-collapse collapse"
            aria-labelledby="headingThree"
            data-bs-parent="#accordionExample"
          >
            <div class="accordion-body">10th January 2023</div>
          </div>
        </div>
      </div>
    </div>
    <div class="container mt-4 py-4">
      <h1 class="my-4 py-4">Conference Sponsers</h1>
      <div class="row">
        <div class="col text-center">
          <img
            src="~/assets/images/opjulogo.png"
            alt="sponser"
            style="width: 90px"
          />
        </div>
        <div class="col">
          <img
            src="~/assets/images/cgcost.png"
            alt="sponser"
            class="cg-cost-img"
          />
        </div>
        <div class="col-12 col-md-auto text-center">
          <img src="~/assets/images/QCI-Logo.png" alt="sponser" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      days: 0,
      hours: 0,
      mins: 0,
      sec: 0,
    }
  },
  mounted() {
    const countDownTimer = new Date('Feb 8, 2023').getTime()

    const x = setInterval(() => {
      const currentTime = new Date().getTime()
      const time = countDownTimer - currentTime

      this.days = Math.floor(time / (1000 * 60 * 60 * 24))
      this.hours = Math.floor((time % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60))
      this.mins = Math.floor((time % (1000 * 60 * 60)) / (1000 * 60))
      this.sec = Math.floor((time % (1000 * 60)) / 1000)

      if (time < 0) {
        clearInterval(x)
      }
    }, 1000)
  },
}
</script>

<style scoped>
.iee-img {
  width: 13rem;
}

.container-fluid {
  position: relative;
  height: 100vh;
  width: 100%;
  /* background-image: url('../assets/images/bg.jpeg'); */
  background-image: linear-gradient(to right, #232526ca, #414345ad),
    url('https://images.unsplash.com/photo-1587825140708-dfaf72ae4b04?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80');
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.hero-content {
  height: 100vh;
}
.o-title {
  font-size: 5rem;
  letter-spacing: 18px;
}

@media (max-width: 682px) {
  .cg-cost-img {
    width: 20rem;
  }
}
</style>
