<template>
  <div>
    <div class="container">
      <div class="row my-2 py-2 bg-light text-sm-center">
        <div class="col-sm-4">
          <nuxt-link class="nav-link" :to="`${$route.path}/callforpapersub`"
            >Camera Ready Submission</nuxt-link
          >
        </div>
        <div class="col-sm-auto">
          <nuxt-link class="nav-link" :to="`${$route.path}/pptinstructions`"
            >PPT Instructions</nuxt-link
          >
        </div>
      </div>
      <div class="row">
        <div class="col-12 col-xl-6">
          <img
            class="img-fluid rounded"
            src="~/assets/images/conf-1.jpg"
            alt="conference image"
          />
        </div>
        <div class="col-12 col-xl-6 mt-2 mt-xl-0 px-4 pe-xl-5">
          <p>
            OTCON 2.0 invites full-length original research contributions from
            researchers/professionals from industries, R&D organizations,
            academic institutions, and government departments from across the
            world. Full-length original research contributions and review
            articles not exceeding six pages as per the IEEE double-column
            format can be submitted. The template for the paper may be
            downloaded from
            <a href="#">here</a>.
            <br />
            <br />
            The manuscript should contribute original research ideas,
            developmental ideas, analysis, findings, results, etc. The
            manuscript should not have been published in any journals/magazines
            or conference proceedings and should not be under review in any of
            them. Further, the manuscript should contain the name of the
            corresponding author with the e-mail id and affiliation of all
            authors.
            <br />
            <br />
            A soft-copy of the full-length manuscripts in IEEE double-column
            format should be submitted electronically via Easy Chair through
            this
            <a href="#">Link</a>. All the submitted manuscripts will be sent for
            peer review and the corresponding author will be notified about the
            outcome of the review process. If reviewers recommended further
            improvement in the manuscript, the manuscript will be sent back to
            the corresponding author and the revised version of the manuscript
            shall be submitted within the due date. The deadlines for submission
            of the manuscript, acceptance notification, camera-ready paper
            submission, and registration will be notified on the conference
            website. Any query regarding submission may be addressed to
            <strong
              >otcon@opju.ac.in. Accepted and presented papers will be submitted
              for inclusion into IEEE Xplore subject to meeting IEEE Xplore’s
              scope and quality requirements.</strong
            >
          </p>
        </div>
        <div class="col-12 mt-xl-4">
          <h2 class="w-100 py-2 rounded text-white text-center bg-primary">
            Paper Selection Process
          </h2>
        </div>
        <div class="col-12">
          <div class="accordion accordion-flush" id="accordionFlushExample">
            <div class="accordion-item">
              <h2 class="accordion-header" id="flush-headingOne">
                <button
                  class="accordion-button collapsed"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#flush-collapseOne"
                  aria-expanded="true"
                  aria-controls="flush-collapseOne"
                >
                  <strong>Step 1</strong>
                </button>
              </h2>
              <div
                id="flush-collapseOne"
                class="accordion-collapse collapse show"
                aria-labelledby="flush-headingOne"
                data-bs-parent="#accordionFlushExample"
              >
                <div class="accordion-body">
                  (Received) Abstracts* / full-length papers received will be
                  given paper ID** relevant to the conference topic and track.
                </div>
              </div>
            </div>
            <div class="accordion-item">
              <h2 class="accordion-header" id="flush-headingTwo">
                <button
                  class="accordion-button collapsed"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#flush-collapseTwo"
                  aria-expanded="false"
                  aria-controls="flush-collapseTwo"
                >
                  <strong>Step 2</strong>
                </button>
              </h2>
              <div
                id="flush-collapseTwo"
                class="accordion-collapse collapse"
                aria-labelledby="flush-headingTwo"
                data-bs-parent="#accordionFlushExample"
              >
                <div class="accordion-body">
                  (Under Screening) Initial screening review will be done by the
                  Technical Program Committee of OTCON 2.0. Initial screening
                  includes relevance to the conference topic, plagiarism***,
                  organization of the paper, quality of
                  figures/diagrams/illustrations/equations and technical
                  novelty, etc.
                </div>
              </div>
            </div>
            <div class="accordion-item">
              <h2 class="accordion-header" id="flush-headingThree">
                <button
                  class="accordion-button collapsed"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#flush-collapseThree"
                  aria-expanded="false"
                  aria-controls="flush-collapseThree"
                >
                  <strong>Step 3</strong>
                </button>
              </h2>
              <div
                id="flush-collapseThree"
                class="accordion-collapse collapse"
                aria-labelledby="flush-headingThree"
                data-bs-parent="#accordionFlushExample"
              >
                <div class="accordion-body">
                  (Under Review) Papers got through Step 2 alone will be
                  forwarded to the technical review process.
                </div>
              </div>
            </div>
            <div class="accordion-item">
              <h2 class="accordion-header" id="flush-headingThree">
                <button
                  class="accordion-button collapsed"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#flush-collapseThree"
                  aria-expanded="false"
                  aria-controls="flush-collapseThree"
                >
                  <strong>Step 4</strong>
                </button>
              </h2>
              <div
                id="flush-collapseThree"
                class="accordion-collapse collapse"
                aria-labelledby="flush-headingThree"
                data-bs-parent="#accordionFlushExample"
              >
                <div class="accordion-body">
                  (Revision) The corresponding author will be notified of the
                  outcome of the review process and the revised version of the
                  manuscript shall be submitted within fifteen days on the date
                  of intimation.
                </div>
              </div>
            </div>
            <div class="accordion-item">
              <h2 class="accordion-header" id="flush-headingThree">
                <button
                  class="accordion-button collapsed"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#flush-collapseThree"
                  aria-expanded="false"
                  aria-controls="flush-collapseThree"
                >
                  <strong>Step 5</strong>
                </button>
              </h2>
              <div
                id="flush-collapseThree"
                class="accordion-collapse collapse"
                aria-labelledby="flush-headingThree"
                data-bs-parent="#accordionFlushExample"
              >
                <div class="accordion-body">
                  (Under Review) A revised version of the papers will be sent to
                  reviewers to ensure that all the suggested corrections have
                  been carried out. If the reviewer is recommended for minor
                  revision, TPC recommends its decision to be taken by the
                  organizing Chair.
                </div>
              </div>
            </div>
            <div class="accordion-item">
              <h2 class="accordion-header" id="flush-headingThree">
                <button
                  class="accordion-button collapsed"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#flush-collapseThree"
                  aria-expanded="false"
                  aria-controls="flush-collapseThree"
                >
                  <strong>Step 6</strong>
                </button>
              </h2>
              <div
                id="flush-collapseThree"
                class="accordion-collapse collapse"
                aria-labelledby="flush-headingThree"
                data-bs-parent="#accordionFlushExample"
              >
                <div class="accordion-body">
                  (Accept / Reject) A final decision will be taken by the
                  organizing chair based on the recommendations by the reviewers
                  / TPC and the same will be intimated to the corresponding
                  authors.
                </div>
              </div>
            </div>
            <div class="accordion-item">
              <h2 class="accordion-header" id="flush-headingThree">
                <button
                  class="accordion-button collapsed"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#flush-collapseThree"
                  aria-expanded="false"
                  aria-controls="flush-collapseThree"
                >
                  <strong>Step 7</strong>
                </button>
              </h2>
              <div
                id="flush-collapseThree"
                class="accordion-collapse collapse"
                aria-labelledby="flush-headingThree"
                data-bs-parent="#accordionFlushExample"
              >
                <div class="accordion-body">
                  (CRP Received / Not Received) status of the Camera-Ready Paper
                  after the acceptance.
                </div>
              </div>
            </div>
            <div class="accordion-item">
              <h2 class="accordion-header" id="flush-headingThree">
                <button
                  class="accordion-button collapsed"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#flush-collapseThree"
                  aria-expanded="false"
                  aria-controls="flush-collapseThree"
                >
                  <strong>Step 8</strong>
                </button>
              </h2>
              <div
                id="flush-collapseThree"
                class="accordion-collapse collapse"
                aria-labelledby="flush-headingThree"
                data-bs-parent="#accordionFlushExample"
              >
                <div class="accordion-body">
                  (REG Complete / Pending) Status of the registration
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-12 mt-4">
          <p class="fs-5 badge text-bg-info">Info</p>
          <p>
            No paper will be accepted without screening review and technical
            review process
          </p>
          <ul>
            <li>
              Full-length papers shall be submitted in order to consider the
              paper for the review process.
            </li>
            <li>
              Paper ID will be provided to all the received papers within ONE
              working day from conference@opju.ac.in. Authors are requested to
              contact the TPC through conference@opju.ac.in if the paper ID has
              not been received within the time frame.
            </li>
            <li>
              TPC of OTCON 2.0 will check for possible plagiarism TWICE, first
              after receiving the paper and then at the stage of acceptance.
              Though OTCON 2.0 will carefully check for plagiarism, there are
              some possibilities for wrong plagiarism results, hence OTCON 2.0
              encourages the authors to take sole responsibility for plagiarism
              when they are ready to submit their papers.
            </li>
          </ul>
          <p>
            <strong>For further details please contact</strong> <br />
            The Organizing Chair, <br />
            OTCON 2.0, <br />
            OP Jindal Institute of Technology, <br />
            Raigarh, Chhattisgarh, India. <br />
            E-mail:
            <a href="mailto: conference@opju.ac.in">conference@opju.ac.in</a>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: 'CallForPaper',
}
</script>