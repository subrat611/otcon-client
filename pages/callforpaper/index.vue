<template>
  <page-wrapper>
    <page-header>
      <h2 class="">Call For Papers</h2>
      <h5 class="mt-3 text-light">
        OPJU INTERNATIONAL TECHNOLOGY CONFERENCE On Emerging Technologies for
        Sustainable Development (8-10 Feb, 2023)
      </h5>
    </page-header>
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
        <div class="col-lg-6">
          <a
            href="https://easychair.org/conferences/?conf=otcon2022"
            target="_blank"
          >
            <img
              class="img-fluid rounded"
              src="~/assets/images/otweb-img.png"
              alt="conference image"
            />
          </a>
          <h3 class="py-2 my-3 rounded text-white text-center bg-info">
            Paper Selection Process
          </h3>

          <div class="process">
            <ul class="list-group list-group-flush mb-5">
              <li
                v-for="(step, i) in selectionProcess"
                :key="i"
                class="list-group-item"
              >
                <h6>Step {{ i + 1 }}</h6>
                {{ step.step }}
              </li>
            </ul>
          </div>

          <div class="alert alert-info">
            No paper will be accepted without screening review and technical
            review process
          </div>
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
          <div class="alert alert-info">
            <strong>For further details please contact</strong> <br />
            The Organizing Chair, <br />
            OTCON 2.0, <br />
            OP Jindal Institute of Technology, <br />
            Raigarh, Chhattisgarh, India. <br />
            E-mail:
            <a href="mailto: OTCON@OPJU.AC.IN">OTCON@OPJU.AC.IN</a>
          </div>
        </div>
        <div class="col-lg-6">
          <h5 class="fw-bold mb-3">
            OPJU INTERNATIONAL TECHNOLOGY CONFERENCE On Emerging Technologies
            for Sustainable Development (8-10 Feb, 2023)
          </h5>
          <p>
            OTCON 2.0 invites full-length original research contributions from
            researchers/professionals from industries, R&D organizations,
            academic institutions, and government departments from across the
            world. Full-length original research contributions and review
            articles not exceeding six pages as per the IEEE double-column
            format can be submitted. The template for the paper may be
            downloaded from
            <a
              href="https://www.ieee.org/content/dam/ieee-org/ieee/web/org/conferences/Conference-template-A4.doc"
              >here</a
            >.
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
            <a
              href="https://easychair.org/conferences/?conf=otcon2022"
              target="_blank"
              >Link</a
            >. All the submitted manuscripts will be sent for peer review and
            the corresponding author will be notified about the outcome of the
            review process. If reviewers recommended further improvement in the
            manuscript, the manuscript will be sent back to the corresponding
            author and the revised version of the manuscript shall be submitted
            within the due date. The deadlines for submission of the manuscript,
            acceptance notification, camera-ready paper submission, and
            registration will be notified on the conference website. Any query
            regarding submission may be addressed to
            <strong
              >otcon@opju.ac.in. Accepted and presented papers will be submitted
              for inclusion into IEEE Xplore subject to meeting IEEE Xplore’s
              scope and quality requirements.</strong
            >
          </p>
        </div>
      </div>
    </div>
  </page-wrapper>
</template>

<script>
import pageWrapper from '~/components/page-wrapper.vue'
export default {
  components: { pageWrapper },
  name: 'CallForPaper',
  data() {
    return {
      selectionProcess: [
        {
          step: `Received) Abstracts* / full-length papers received will be given paper ID** relevant to the conference topic and track.`,
        },
        {
          step: `
(Under Screening) Initial screening review will be done by the Technical Program Committee of OTCON 2.0. Initial screening includes relevance to the conference topic, plagiarism***, organization of the paper, quality of figures/diagrams/illustrations/equations and technical novelty, etc.`,
        },
        {
          step: `(Under Review) Papers got through Step 2 alone will be forwarded to the technical review process.`,
        },
        {
          step: `(Revision) The corresponding author will be notified of the outcome of the review process and the revised version of the manuscript shall be submitted within fifteen days on the date of intimation.
`,
        },
        {
          step: `(Under Review) A revised version of the papers will be sent to reviewers to ensure that all the suggested corrections have been carried out. If the reviewer is recommended for minor revision, TPC recommends its decision to be taken by the organizing Chair.`,
        },
        {
          step: `(Accept / Reject) A final decision will be taken by the organizing chair based on the recommendations by the reviewers / TPC and the same will be intimated to the corresponding authors.`,
        },
        {
          step: `(CRP Received / Not Received) status of the Camera-Ready Paper after the acceptance.`,
        },
        {
          step: `(REG Complete / Pending) Status of the registration`,
        },
      ],
    }
  },
  head: {
    title: 'Call For Papers | OPJU International Technology Conference | 2022',
  },
}
</script>
