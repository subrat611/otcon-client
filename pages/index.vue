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
    <div class="noitce">
      <marquee class="alert alert-info" behavior="scroll"
        >Accepted and presented papers will be submitted for inclusion into IEEE
        Xplore</marquee
      >
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
    <div class="container mt-4 py-4"></div>
    <div class="container">
      <div class="row">
        <div class="col-lg-8">
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Alias qui
          dolorem omnis aliquam? Veniam error dolorum labore! Cum odit nemo
          repellat dolore explicabo quos voluptates ratione exercitationem,
          numquam voluptatibus alias nihil aliquam illum, molestias sint vitae
          facilis eos quam blanditiis! Culpa saepe voluptatibus delectus
          voluptatem at incidunt dolorum quo, numquam placeat fugiat iusto
          magni, facilis exercitationem ratione error cupiditate vitae
          voluptates provident tempore nobis quidem sapiente! Deserunt eveniet,
          fuga nobis corrupti corporis eligendi rerum nihil minima!
          Exercitationem veniam facere voluptas facilis ad quidem dolorem et
          optio cupiditate, eos magnam repellat quasi libero dolor repudiandae
          sequi officiis quis molestias excepturi? Modi blanditiis, aliquam
          excepturi quas in cupiditate vero nisi provident vel! Aliquam,
          quaerat, doloremque repellendus nihil nam veniam corrupti adipisci
          architecto rem obcaecati illo? Nisi rerum, eaque fuga excepturi qui
          incidunt commodi perspiciatis enim similique natus assumenda iure nam
          dolorum, alias expedita dignissimos veniam recusandae blanditiis,
          harum sint ea officiis dolore. Dignissimos nobis ipsum at a! Eaque
          libero non asperiores nihil ducimus pariatur? Adipisci necessitatibus
          porro voluptatibus quaerat hic assumenda at aut natus quae! Expedita
          est officiis quibusdam commodi voluptate sed amet, assumenda possimus
          magnam quidem quisquam repellat eveniet, laudantium asperiores?
          Maiores reprehenderit eligendi molestiae ullam iusto fugit minima
          doloremque in. Libero ut neque molestias unde. Quis veniam debitis
          porro expedita eligendi qui laborum libero consectetur fugit, maiores
          necessitatibus in vero aliquam aperiam! Libero minus ipsam excepturi
          ad, officia cumque expedita, odit culpa est aliquam modi sequi iure
          suscipit eum, corporis quod doloribus dolores voluptates accusamus.
          Ullam numquam laborum, pariatur enim, aliquam ipsum facere
          reprehenderit tenetur magnam ab omnis nisi quo expedita cupiditate
          consequuntur inventore magni. Quibusdam id laudantium, cumque eveniet
          velit minus vero quis, qui ratione, quasi optio tenetur. Explicabo
          quisquam nemo repellendus laborum enim, vero, rem nisi obcaecati autem
          corporis magnam officiis adipisci porro distinctio quod unde eum. At
          delectus distinctio consequuntur commodi qui quas repudiandae eligendi
          architecto. Quas esse reprehenderit debitis ea rerum, ex eveniet
          veniam fuga, ullam obcaecati quo vitae odio aliquid. Error porro neque
          alias natus, dolorum labore maiores facilis sequi magni molestias
          possimus quo? Facere, autem molestias nobis deserunt voluptates,
          corrupti assumenda exercitationem alias illum velit tempora nemo
          consequatur, ea rem accusamus quae omnis labore architecto voluptas!
          Beatae doloribus culpa libero accusantium ab assumenda veniam quidem
          necessitatibus, a cum optio quaerat iste blanditiis dolore asperiores
          minus officiis nostrum veritatis dolor dicta ipsam pariatur? Amet
          sequi quia perspiciatis cum autem, quo quisquam assumenda repudiandae
          labore eos pariatur doloribus corporis modi maxime ipsum. Deserunt
          accusamus ipsum, saepe maiores debitis consequuntur ipsa eius iste
          natus atque velit quo? Voluptatum expedita, aliquam eius cumque
          debitis quae, culpa velit ratione pariatur corrupti necessitatibus qui
          autem, dolorum doloremque ex architecto aperiam fugit facilis officia
          ipsum eligendi adipisci? Magni minima quidem atque fuga vel eaque
          veritatis reprehenderit accusamus iusto unde illum cumque esse
          tenetur, aliquid suscipit sed praesentium, rem nihil autem, aperiam
          distinctio consequatur tempora. Doloremque sint odio iste quod,
          necessitatibus, est accusamus atque vitae voluptatem adipisci ratione
          suscipit commodi omnis eaque veniam tempore blanditiis quibusdam
          officia! Exercitationem, nihil cupiditate dicta pariatur rem quae
          porro quam vitae minima omnis quas est illum saepe? Doloremque
          perspiciatis quasi cumque libero praesentium modi dolorum, vero optio
          est labore eveniet facilis dicta atque corrupti beatae saepe tempore
          impedit officiis. Nostrum, enim labore minus id, dolorem quibusdam,
          similique voluptatum nihil temporibus necessitatibus odit? Cum magni
          tenetur nesciunt culpa dolore labore minima ab pariatur. Numquam
          aperiam dolor aspernatur delectus molestias quidem in, reprehenderit
          sit eos ipsum iusto minima similique labore, quae vitae corporis!
          Soluta accusamus consequatur deserunt officiis saepe, harum obcaecati
          corporis iusto, voluptates facilis ullam nostrum dolore, odio
          cupiditate. Tenetur adipisci similique est modi repellat praesentium
          ad sit culpa magnam cupiditate, porro nisi atque esse eaque eius
          aspernatur qui ullam delectus a eligendi eum. Perferendis fugiat neque
          velit dolorum. Magni libero aliquid deleniti, mollitia dicta corrupti
          eveniet praesentium. Tenetur aperiam deserunt debitis, accusamus
          reiciendis ea. Est eaque voluptatem cum nisi eum quas quae, sapiente
          cupiditate ipsam qui iste sit suscipit harum dicta iure. Deleniti
          mollitia ea provident nostrum, consequuntur voluptate obcaecati
          eligendi distinctio earum vero quos perspiciatis inventore fuga rerum.
          Optio minus fugiat dolorum eos odio fugit repellendus ab quia quidem
          nulla quod, impedit consectetur id esse error perspiciatis porro omnis
          alias asperiores illum soluta officia dolore dicta expedita? Soluta
          laboriosam vitae assumenda reiciendis nemo sunt obcaecati magnam ad
          perspiciatis, at sapiente inventore officiis pariatur, dolor iure,
          quos quibusdam consectetur modi. Quo magni qui adipisci sed ullam
          expedita quasi, inventore facilis ducimus dolor illo voluptatibus
          impedit sapiente excepturi, labore officia, recusandae eum. Eveniet
          totam minima id ipsam quasi exercitationem, nihil maxime possimus
          voluptatum qui corporis, eligendi ducimus veritatis architecto quae
          quos facere adipisci. Laborum reiciendis consectetur quod sit,
          consequuntur excepturi natus, ipsum, porro voluptate aspernatur eos
          accusamus nostrum? Saepe natus ullam id ipsa assumenda consequuntur
          aperiam, laboriosam dolorem possimus quis veritatis aliquam, illo,
          quisquam eos. Sit molestiae delectus maiores quis placeat fuga optio
          animi consequuntur? Libero eaque, molestias est provident amet quo
          omnis, placeat odit tenetur, unde optio commodi. Hic eum, ipsum non,
          doloribus magnam eaque consectetur accusantium vitae quibusdam, optio
          animi facilis voluptate maiores minima architecto? Enim iure nesciunt
          quibusdam veritatis rerum doloribus neque quae expedita explicabo?
          Consectetur nostrum amet mollitia debitis, obcaecati vitae tenetur
          rerum facere fugiat, laboriosam repellat cumque inventore dicta
          doloribus hic labore minima sequi odit tempora ut. Provident, quidem,
          culpa reprehenderit libero officia at laborum distinctio pariatur
          ipsam saepe commodi accusamus ex unde tempora aliquam. Obcaecati illo
          eius animi commodi libero tempora, enim ea reiciendis, impedit
          recusandae nisi. Illo, vitae cupiditate distinctio molestias,
          explicabo minus reprehenderit ab quos quaerat atque debitis numquam!
          Architecto commodi alias, expedita at, ipsa fugit consectetur saepe
          animi consequuntur itaque odit odio vero exercitationem quo nemo
          quisquam eveniet dolore, illum ab suscipit a aliquam! Minus facere at
          vero repellat odit. Libero repudiandae amet delectus eveniet deserunt
          tempore, sunt quam at, iusto cumque harum voluptas dignissimos
          provident a vel, ad suscipit. Officia exercitationem doloribus fugit
          quia eligendi? In perspiciatis aut corrupti? Vero cumque laudantium
          officiis iste debitis voluptas quod impedit. Omnis iure numquam nihil
          at quae ut est exercitationem!
        </div>
        <div class="col-lg-4">
          <div class="important-dates sticky-top py-5">
            <h5 class="py-4">Important Dates</h5>
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

.timer {
  color: skyblue;
}

.timer:hover {
  background: rgba(255, 255, 255, 0.707);
}
</style>
