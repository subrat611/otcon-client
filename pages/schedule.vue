<template>
  <page-wrapper>
    <page-header>
      <h2>Conference Schedule</h2>
    </page-header>
    <div class="container mt-4 py-4">
      <div class="row">
        <div class="col-12 col-sm-6">
          <img src="~/static/inaugural.png" class="inaugural-img" />
        </div>
        <div class="col-12 col-sm-6">
          <div class="important-dates sticky-top py-5 mb-2">
            <h5 class="py-4">Conference Schedule</h5>
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
                    <strong>Inaugural Schedule (Day 1) </strong>
                  </button>
                </h2>
                <div
                  id="collapseOne"
                  class="accordion-collapse collapse show"
                  aria-labelledby="headingOne"
                  data-bs-parent="#accordionExample"
                >
                  <div class="accordion-body">
                    <div class="o-schedule-box">
                      <img
                        src="~/static/inauguralSchedule.png"
                        class="schedule-img"
                      />

                      <div class="overlay">
                        <button class="btn btn-primary shadow-lg">
                          <a
                            href="/inauguralSchedule.png"
                            download="Inaugural Schedule (Day 1)"
                          >
                            Download Schedule
                          </a>
                        </button>
                        <div>
                          <button
                            class="o-custom-btn btn border-primary shadow-lg"
                          >
                            <img
                              src="~/static/zoom.png"
                              style="margin: 0 0.5rem"
                            />
                            <a
                              href="https://us06web.zoom.us/j/87836298916?pwd=M3ZHVGh1ckYzV0JKNzd3NjhOdDBWZz09"
                              target="_blank"
                              >Attend online</a
                            >
                          </button>
                          <p class="text-light fw-semibold mt-1 text-center">
                            Passcode: 124009
                          </p>
                        </div>
                      </div>
                    </div>
                  </div>
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
                    <strong
                      >Technical Session ( Day 2 and Day 3) Schedule
                    </strong>
                  </button>
                </h2>
                <div
                  id="collapseTwo"
                  class="accordion-collapse collapse"
                  aria-labelledby="headingTwo"
                  data-bs-parent="#accordionExample"
                >
                  <div class="accordion-body">
                    <div class="o-schedule-box">
                      <img src="~/static/day2and3.png" class="schedule-img" />

                      <div class="overlay">
                        <button class="btn btn-primary shadow-lg">
                          <a
                            href="/day2and3.pdf"
                            download="OTCON Keynote and Technical Session Schedule Day-02 and Day-03"
                          >
                            Download Schedule
                          </a>
                        </button>
                        <div class="text-center mt-3">
                          <p class="m-0 text-light fw-semibold">
                            Keynote Session I_OTCON 2.0
                          </p>
                          <button
                            class="o-custom-btn btn border-primary shadow-lg"
                          >
                            <img
                              src="~/static/zoom.png"
                              style="margin: 0 0.5rem"
                            />
                            <a
                              href="https://us06web.zoom.us/j/87977042898?pwd=ckNhdHNHbTJUWlJaU0RGZGhUM0hDZz09"
                              target="_blank"
                              >Attend online</a
                            >
                          </button>
                          <p class="text-light fw-semibold mt-1 text-center">
                            Passcode: 714493
                          </p>
                        </div>
                        <div class="text-center mt-3">
                          <p class="m-0 text-light fw-semibold">
                            Keynote Session II_OTCON 2.0
                          </p>
                          <button
                            class="o-custom-btn btn border-primary shadow-lg"
                          >
                            <img
                              src="~/static/zoom.png"
                              style="margin: 0 0.5rem"
                            />
                            <a
                              href="https://us06web.zoom.us/j/84272369529?pwd=UUE2aTNYblZSSVdaaHYzdE4vcDFRZz09"
                              target="_blank"
                              >Attend online</a
                            >
                          </button>
                          <p class="text-light fw-semibold mt-1 text-center">
                            Passcode: 446832
                          </p>
                        </div>
                      </div>
                    </div>
                  </div>
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
                    <strong>Valedictory Session (Day3) Schedule</strong>
                  </button>
                </h2>
                <div
                  id="collapseThree"
                  class="accordion-collapse collapse"
                  aria-labelledby="headingThree"
                  data-bs-parent="#accordionExample"
                >
                  <div class="accordion-body">
                    <div class="o-schedule-box">
                      <img
                        src="~/static/day3valedictory.png"
                        class="schedule-img"
                      />

                      <div class="overlay">
                        <button class="btn btn-primary shadow-lg">
                          <a
                            href="/Day-03Valedictory.pdf"
                            download="OTCON-Schedule for Day-03 Valedictory"
                          >
                            Download Schedule
                          </a>
                        </button>
                        <div>
                          <button
                            class="o-custom-btn btn border-primary shadow-lg"
                          >
                            <img
                              src="~/static/zoom.png"
                              style="margin: 0 0.5rem"
                            />
                            <a
                              href="https://us06web.zoom.us/j/89163805918?pwd=L0dLeFIrUmJaaVRjTmdNTCtueFhwdz09"
                              target="_blank"
                              >Attend online</a
                            >
                          </button>
                          <p class="text-light fw-semibold mt-1 text-center">
                            Passcode: 850077
                          </p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </page-wrapper>
</template>

<script>
export default {
  name: 'ConferenceSchedule',
}
</script>

<style scoped>
a {
  text-decoration: none;
  color: aliceblue;
}

.inaugural-img,
.schedule-img {
  width: 100%;
  height: 100%;
}

.o-schedule-box {
  position: relative;
}

.o-custom-btn {
  border: 2px solid #0956b5;
  outline: none;
  margin-top: 1rem;
}

.overlay {
  position: absolute;
  top: 0;
  height: 100%;
  width: 100%;
  background-color: rgba(0, 0, 0, 0.77);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
