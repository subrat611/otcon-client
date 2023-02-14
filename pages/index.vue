<template>
  <div>
    <div class="container-fluid">
      <!-- header -->
      <div class="container text-center">
        <div class="row align-items-center hero-content pt-5">
          <div class="col-12">
            <img
              src="../assets/images/ieeemp.jpg"
              alt="iee image"
              class="iee-img"
            />
          </div>
          <div class="col-12">
            <p data-aos="fade-up" class="o-title text-light fw-bolder">
              OTCON 2.0
            </p>
            <p class="text-light fs-3 o-desc">
              OPJU INTERNATIONAL TECHNOLOGY CONFERENCE <br />On Emerging
              Technologies for Sustainable Development (8-10 Feb, 2023)
              <br />
              <span
                class="text-warning fw-semibold"
                style="font-size: 1rem; letter-spacing: 0.1rem"
                ><i>Hybrid Mode</i></span
              >
              <br />
              <span class="text-info" style="font-size: 1.2rem"
                >Venue: O.P. Jindal University, Raigarh, Chhattisgarh,
                India.</span
              >
            </p>
          </div>
          <h5 class="text-light text-uppercase fw-bolder">Event Starts In</h5>
          <div
            class="col-12 text-light d-flex justify-content-center align-items-center mb-5 pb-3"
          >
            <div class="col-2 col-md-1 border rounded me-4 pt-4">
              <h3 class="timer">{{ days }}</h3>
              <p>days</p>
            </div>
            <div class="me-3"><h2>:</h2></div>
            <div class="col-2 col-md-1 border rounded me-4 pt-4">
              <h3 class="timer">{{ hours }}</h3>
              <p>hours</p>
            </div>
            <div class="me-3"><h2>:</h2></div>
            <div class="col-2 col-md-1 border rounded me-4 pt-4">
              <h3 class="timer">{{ mins }}</h3>
              <p>mins</p>
            </div>
            <div class="me-3"><h2>:</h2></div>
            <div class="col-2 col-md-1 border rounded pt-4">
              <h3 class="timer">{{ sec }}</h3>
              <p>sec</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- notice -->
    <div class="noitce">
      <marquee class="alert alert-info" behavior="scroll"
        >Accepted and presented papers will be submitted for inclusion into IEEE
        Xplore</marquee
      >
    </div>
    <div class="container mt-4 py-4"></div>
    <div class="container">
      <div class="row">
        <div class="col-lg-8">
          <!-- conference tracks -->
          <div class="">
            <h4 class="py-4">Conference Tracks</h4>
            <div class="row">
              <div
                v-for="(track, index) in tracks"
                :key="index"
                class="col-lg-6 col-sm-12 mb-3"
              >
                <div class="card text-center d-flex align-items-center">
                  <img class="track-img" :src="track.img" :alt="track.title" />
                  <h6 class="mb-4">{{ track.title }}</h6>
                </div>
                <div
                  v-for="(data, index) in track.subTrack"
                  :key="index"
                  class="border-start border-success border-2 pt-2 ms-2 mb-0"
                >
                  <p class="ps-3 mb-0 pt-2">{{ data }}</p>
                </div>
              </div>
            </div>
          </div>

          <!-- About Conference -->
          <div class="my-3 py-5 pe-2">
            <h1 class="py-3">About Conference</h1>
            <p class="px-2">
              The <b>OTCON</b> aims to be a premier conference in Central India
              and will provide a platform for researchers, academicians, working
              professionals, students and government personnel from various
              engineering fields to share and discuss the latest emerging
              technologies and related research for sustainable development,
              especially in the domain of
              <strong
                >Intelligent Computing, Communication, Control, Networking,
                Renewable Energy, Power Systems, IoT, Automation, Manufacturing,
                Signal and Image Processing, Cyber-Physical Systems, Metaverse,
                Education, Environment, and Economics </strong
              >.The conference will witness multiple eminent keynote speakers
              from academia and industry from all over the world along with the
              presentation of accepted peer-reviewed articles.The
              after-conference proceeding of the OTCON Will be submitted for
              inclusion to IEEE XPLORE.
            </p>
          </div>

          <!-- About section -->
          <div class="my-3 py-5 pe-2">
            <h1 class="py-3">About OPJU</h1>
            <p class="px-2">
              OP Jindal University (OPJU) has been established under the aegis
              of the Jindal Education and Welfare Society. The O P Jindal Group
              is a US$ 22 billion conglomerate, employing more than 50,000
              people with manufacturing facilities across India, the US, UK,
              Australia, Indonesia, South Africa, Chile & Mozambique. OPJU is a
              multidisciplinary university aimed at developing young
              professionals and future leaders who will not only power the
              growth and development of the nation but also become responsible
              citizens of the world. At the core of the university's philosophy
              and approach lies the belief that students learn best when exposed
              to real-world situations and when nurtured through enriching
              interactions with practitioners and professors. Website:
              <a href="https://www.opju.ac.in/" target="_blank"
                >www.opju.ac.in</a
              >
            </p>
          </div>

          <!-- Conference Sponsor -->
          <div class="sponsors">
            <h1 class="my-4 py-4">Conference Sponsors</h1>
            <div class="row">
              <div class="col text-center">
                <img
                  class="sponsor-logo"
                  src="~/assets/images/opjulogo.png"
                  alt="sponser"
                  style="width: 90px; height: 90px"
                />
              </div>
              <div class="col">
                <img
                  src="~/assets/images/cgcost.png"
                  alt="sponser"
                  class="sponsor-logo"
                  style="width: 20rem; height: 90px"
                />
              </div>
            </div>
          </div>
          <div class="sponsors my-5">
            <h1 class="my-4 py-4">Technical Sponsor</h1>
            <div class="row">
              <div class="col text-center">
                <img
                  class="sponsor-logo"
                  src="~/assets/images/ieeemp.jpg"
                  alt="sponser"
                  style="width: 300px; height: 110px"
                />
              </div>
            </div>
          </div>
        </div>

        <!-- fixed right section -->
        <div class="col-lg-4">
          <div class="important-dates sticky-top py-5 mb-2">
            <h5 class="py-4">Important Dates</h5>
            <div id="accordionExample" class="accordion">
              <div class="accordion-item">
                <h2 id="headingOne" class="accordion-header">
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
            <div class="accordion mt-5" id="accordionPanelsStayOpenExample">
              <div class="accordion-item">
                <h2 class="accordion-header" id="panelsStayOpen-headingOne">
                  <button
                    class="accordion-button"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#panelsStayOpen-collapseOne"
                    aria-expanded="true"
                    aria-controls="panelsStayOpen-collapseOne"
                  >
                    <strong>Important Links</strong>
                  </button>
                </h2>
                <div
                  id="panelsStayOpen-collapseOne"
                  class="accordion-collapse collapse show"
                  aria-labelledby="panelsStayOpen-headingOne"
                >
                  <div class="accordion-body">
                    <a
                      href="https://easychair.org/conferences/?conf=otcon2022"
                      target="_blank"
                    >
                      Submit Paper »
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
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
      tracks: [
        {
          title: 'Emerging And Intelligent Computing',
          img: 'https://cdn-icons-png.flaticon.com/64/2821/2821637.png',
          subTrack: [
            'Artificial Intelligence, and Machine Learning',
            'Blockchain Technologies',
            'Cloud and Distributed Computing',
            'Data Sciences',
            'Geographic Information System',
            'Human-Computer Interactions',
            'Quantum Computing',
            'Software Architectures, and Design Patterns',
          ],
        },
        {
          title: 'Communication Control And Networking',
          img: 'https://cdn-icons-png.flaticon.com/64/2821/2821637.png',
          subTrack: [
            'Cognitive Radio System',
            'Edge Computing and 5G',
            'Feedback Control System',
            'Instrumentation And Control',
            'Mobile And optical Communication',
            'Sensor Network',
            'Social and Smart Networking',
            'Wireless Communication',
          ],
        },
        {
          title: 'Renewable Energy And Power System',
          img: 'https://cdn-icons-png.flaticon.com/64/2821/2821637.png',
          subTrack: [
            'Electrical Vehicle, and Charging Techniques',
            'Energy Efficient Drives',
            'Energy harvesting, and Storage Techniques',
            'High-voltage Engineering, and Technologies',
            'Power Electronics, and Its Application',
            'Power Quality Improvement Techniques',
            'Renewable Energy Technologies, and Issues',
            'Renewable Power Conversion Technologies',
            'Smart-grid Technologies, and Issues',
            'Soft Computing in Power Systems',
          ],
        },
        {
          title: 'Bio Informatics And Health Care',
          img: 'https://cdn-icons-png.flaticon.com/64/2821/2821637.png',
          subTrack: [
            'Biomedical Intelligence, and Computing',
            'Biomedical Signal, and Image Processing',
            'Biotechnology, and Pharmaceutical',
            'Healthcare Informatics, and Support System',
            'Immunology Informatics',
            'Medical Diagnostics Informatics',
            'Remote Healthcare',
            'Smart Clinical Trails',
          ],
        },
        {
          title: 'IoT Automation And Manufacturing',
          img: 'https://cdn-icons-png.flaticon.com/64/2821/2821637.png',
          subTrack: [
            'AI-Driven Industrial Automation',
            'IoT-based Smart Systems',
            'Human-Machine Communication',
            'Precision Agriculture',
            'Robotics Process Automation',
            'Sensors and Actuators',
            'Smart and Intelligent Manufacturing',
            'Smart Cities and Villages',
          ],
        },
        {
          title: 'Signal And Image Processing',
          img: 'https://cdn-icons-png.flaticon.com/64/2821/2821637.png',
          subTrack: [
            'Cognitive Information Processing',
            'Computer Vision and Image Analysis',
            'Digital Video and Image Processing',
            'Features Detection',
            'Pattern Recognition',
            'Speech and Language Processing',
            'Statistical Signal Processing',
            'Devices and Signal Processing',
          ],
        },
        {
          title: 'Cyber Physical System And Metaverse',
          img: 'https://cdn-icons-png.flaticon.com/64/2821/2821637.png',
          subTrack: [
            'Augmented and Virtual Reality',
            'Cryptocurrencies',
            'Cryptography',
            'Gamification',
            'Non-Fungible Tokens (NFTs)',
            'Security and Privacy Issues',
            'Security Framework, Protocol, and Architectures',
            'Trustless Systems',
          ],
        },
        {
          title: 'Education Environment And Economics',
          img: 'https://cdn-icons-png.flaticon.com/64/2821/2821637.png',
          subTrack: [
            'Business Intelligence',
            'Digital and Internet Economics',
            'Digital Finance',
            'Digital Marketing',
            'E-Commerce',
            'Industrial Waste Management and Recycling System',
            'Informatics for Economic planning',
            'Intelligent eLearning System',
            'Learning Analytics and Evaluation System',
            'Remote Education Solutions',
            'Solid and Water Waste Management and Recycling System',
            'Sustainable and Digital Entrepreneurship',
            'Virtual Classroom and Metaverse',
          ],
        },
      ],
    }
  },
  head: {
    title: 'OTCON 2.0 | OPJU International Technology Conference | 2022',
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
        this.days = 0
        this.hours = 0
        this.mins = 0
        this.sec = 0
      }
    }, 1000)
  },
}
</script>

<style scoped>
.iee-img {
  width: 18rem;
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
  font-size: 4.5rem;
  letter-spacing: 18px;
}
.o-desc {
  color: #ebf5f7 !important;
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
  .iee-img {
    width: 15rem;
  }
  .cg-cost-img {
    width: 20rem;
  }
  .o-title {
    font-size: 2.5rem;
    letter-spacing: 0.2rem;
  }
  .o-desc {
    font-size: 1rem !important;
  }
}

.timer {
  color: skyblue;
}

.track-img {
  width: 70px;
  height: auto;
  margin: 1rem;
}

.sponsor-logo {
  width: auto;
  height: 70px;
}
</style>
