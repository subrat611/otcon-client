<template>
  <div>
    <div class="container-fluid pt-5">
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
            <p data-aos="fade-up" class="o-title text-light fw-bolder">
              OTCON 2.0
            </p>
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
      <div class="o-conf-track">
        <div class="o-conf-track-data">
          <div>
            <img
              src="https://cdn-icons-png.flaticon.com/64/8389/8389222.png"
              alt="icon"
              class="img-fluid rounded-start py-3"
            />
            <h5 class="fw-semibold">Emerging And Intelligent Computing</h5>
          </div>
          <ol class="track-data-items">
            <li>Artificial Intelligence, and Machine Learning</li>
            <li>Blockchain Technologies</li>
            <li>Cloud and Distributed Computing</li>
            <li>Data Sciences</li>
            <li>Geographic Information System</li>
            <li>Human-Computer Interactions</li>
            <li>Quantum Computing</li>
            <li>Software Architectures, and Design Patterns</li>
          </ol>
        </div>
        <div class="o-conf-track-data">
          <div>
            <img
              src="https://cdn-icons-png.flaticon.com/64/8389/8389099.png"
              alt="icon"
              class="img-fluid rounded-start py-3"
            />
            <h5 class="fw-semibold">Communication, Control, and Networking</h5>
          </div>
          <ol class="track-data-items">
            <li>Cognitive Radio System</li>
            <li>Edge Computing and 5G</li>
            <li>Feedback Control System</li>
            <li>Instrumentation And Control</li>
            <li>Mobile And optical Communication</li>
            <li>Sensor Network</li>
            <li>Social and Smart Networking</li>
            <li>Wireless Communication</li>
          </ol>
        </div>
        <div class="o-conf-track-data">
          <div>
            <img
              src="https://cdn-icons-png.flaticon.com/64/4515/4515708.png"
              alt="icon"
              class="img-fluid rounded-start py-3"
            />
            <h5 class="fw-semibold">Renewable Energy, and Power System</h5>
          </div>
          <ol class="track-data-items">
            <li>Electrical Vehicle, and Charging Techniques</li>
            <li>Energy Efficient Drives</li>
            <li>Energy harvesting, and Storage Techniques</li>
            <li>High-voltage Engineering, and Technologies</li>
            <li>Power Electronics, and Its Application</li>
            <li>Power Quality Improvement Techniques</li>
            <li>Renewable Energy Technologies, and Issues</li>
            <li>Renewable Power Conversion Technologies</li>
            <li>Smart-grid Technologies, and Issues</li>
            <li>Soft Computing in Power Systems</li>
          </ol>
        </div>
        <div class="o-conf-track-data">
          <div>
            <img
              src="https://cdn-icons-png.flaticon.com/64/8389/8389099.png"
              alt="icon"
              class="img-fluid rounded-start py-3"
            />
            <h5 class="fw-semibold">Bio-Informatics, and Healthcare</h5>
          </div>
          <ol class="track-data-items">
            <li>Biomedical Intelligence, and Computing</li>
            <li>Biomedical Signal, and Image Processing</li>
            <li>Biotechnology, and Pharmaceutical</li>
            <li>Healthcare Informatics, and Support System</li>
            <li>Immunology Informatics</li>
            <li>Medical Diagnostics Informatics</li>
            <li>Remote Healthcare</li>
            <li>Smart Clinical Trails</li>
          </ol>
        </div>
        <div class="o-conf-track-data">
          <div>
            <img
              src="https://cdn-icons-png.flaticon.com/64/8389/8389099.png"
              alt="icon"
              class="img-fluid rounded-start py-3"
            />
            <h5 class="fw-semibold">IoT Automation, and Manufacturing</h5>
          </div>
          <ol class="track-data-items">
            <li>AI-Driven Industrial Automation</li>
            <li>IoT-based Smart Systems</li>
            <li>Human-Machine Communication</li>
            <li>Precision Agriculture</li>
            <li>Robotics Process Automation</li>
            <li>Sensors and Actuators</li>
            <li>Smart and Intelligent Manufacturing</li>
            <li>Smart Cities and Villages</li>
          </ol>
        </div>
        <div class="o-conf-track-data">
          <div>
            <img
              src="https://cdn-icons-png.flaticon.com/64/8389/8389099.png"
              alt="icon"
              class="img-fluid rounded-start py-3"
            />
            <h5 class="fw-semibold">Signal and Image Processing</h5>
          </div>
          <ol class="track-data-items">
            <li>Cognitive Information Processing</li>
            <li>Computer Vision and Image Analysis</li>
            <li>Digital Video and Image Processing</li>
            <li>Features Detection</li>
            <li>Pattern Recognition</li>
            <li>Speech and Language Processing</li>
            <li>Statistical Signal Processing</li>
            <li>Devices and Signal Processing</li>
          </ol>
        </div>
        <div class="o-conf-track-data">
          <div>
            <img
              src="https://cdn-icons-png.flaticon.com/64/8389/8389099.png"
              alt="icon"
              class="img-fluid rounded-start py-3"
            />
            <h5 class="fw-semibold">Cyber-Physical System and Metaverse</h5>
          </div>
          <ol class="track-data-items">
            <li>Augmented and Virtual Reality</li>
            <li>Cryptocurrencies</li>
            <li>Cryptography</li>
            <li>Gamification</li>
            <li>Non-Fungible Tokens (NFTs)</li>
            <li>Security and Privacy Issues</li>
            <li>Security Framework, Protocol, and Architectures</li>
            <li>Trustless Systems</li>
          </ol>
        </div>
        <div class="o-conf-track-data">
          <div>
            <img
              src="https://cdn-icons-png.flaticon.com/64/8389/8389099.png"
              alt="icon"
              class="img-fluid rounded-start py-3"
            />
            <h5 class="fw-semibold">Education, Environment, and Economics</h5>
          </div>
          <ol class="track-data-items">
            <li>Business Intelligence</li>
            <li>Digital and Internet Economics</li>
            <li>Digital Finance</li>
            <li>Digital Marketing</li>
            <li>E-Commerce</li>
            <li>Industrial Waste Management and Recycling System</li>
            <li>Informatics for Economic planning</li>
            <li>Intelligent eLearning System</li>
            <li>Learning Analytics and Evaluation System</li>
            <li>Remote Education Solutions</li>
            <li>Solid and Water Waste Management and Recycling System</li>
            <li>Sustainable and Digital Entrepreneurship</li>
            <li>Virtual Classroom and Metaverse</li>
          </ol>
        </div>

        <!-- <div class="col-6">
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
        </div> -->
        <!-- <div class="col">
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
        </div> -->
      </div>
    </div>
    <div class="container mt-4 py-4">
      <h1 class="py-4">Important Dates</h1>
      <div class="row mt-5">
        <div class="col-12 d-flex align-items-center text-center">
          <div class="col-2 p-2 py-5 o-border-date-color">
            <h2>
              30th Nov<br />
              2022
            </h2>
          </div>
          <div class="col-5 text-start px-4">
            <h3>Paper Submission Due</h3>
          </div>
        </div>
        <div class="col-12 d-flex align-items-center text-center">
          <div class="col-2 p-2 py-5 o-border-date-color">
            <h2>
              15th Dec<br />
              2022
            </h2>
          </div>
          <div class="col-5 text-start px-4">
            <h3>Notification of Acceptance</h3>
          </div>
        </div>
        <div class="col-12 d-flex align-items-center text-center">
          <div class="col-2 p-2 py-5 o-border-date-color">
            <h2>
              10th Jan<br />
              2023
            </h2>
          </div>
          <div class="col-5 text-start px-4">
            <h3>Camera Ready Submission</h3>
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

.o-conf-track {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
  gap: 20px 20px;
}

.o-conf-track-data {
  border-radius: 0.5em;
  padding: 1em;
  border: 2px solid #000000;
  width: 25rem;
}
.track-data-items li {
  padding: 10px;
}

.o-border-date-color {
  border-right: 2px solid #28c76f !important;
}

@media (max-width: 682px) {
  .cg-cost-img {
    width: 20rem;
  }
}
</style>
