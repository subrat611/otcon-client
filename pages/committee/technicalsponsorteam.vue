<template>
  <page-wrapper>
    <page-header>
      <h2>IEEE MP Section - Office Bearers</h2>
      <p class="text-light">
        The Institute of Electrical and Electronics Engineers, Incorporated
        (IEEE) is a non-profit corporation, incorporated in the state of New
        York on 16 March 1896. As authorized by the IEEE Board of Directors, the
        IEEE Member and Geographic Activities Board (known as IEEE Regional
        Activities Board prior to 1 January 2008) approved the establishment and
        boundaries of the IEEE Madhya Pradesh Section.
      </p>
      <p class="text-light">
        IEEE, an association dedicated to advancing innovation and technological
        excellence for the benefit of humanity, is the world’s largest technical
        professional society. It is designed to serve professionals involved in
        all aspects of the electrical, electronic and computing fields and
        related areas of science and technology that underlie modern
        civilization.
      </p>
      <p class="text-light">
        OP Jindal university is organizing this technical conference under the
        technical sponsorship and guidance of the following office bearers of
        IEEE MP subsection.
      </p>
    </page-header>
    <div class="container my-4 py-4">
      <div class="o-card-container">
        <div
          v-for="({ img, name, desig, email }, i) in committee"
          :key="i"
          class="o-card mb-3"
        >
          <img v-if="img" :src="img" alt="img" class="o-card-img p-0 mb-3" />
          <p class="m-0">{{ name }}</p>
          <h6 class="m-0 text-danger">{{ desig }}</h6>
          <h6 class="mt-2 text-dark">
            {{ !email ? '' : 'Email:' }}<br />
            <a id="email-id" :href="'mailto:' + email">{{ email }}</a>
          </h6>
        </div>
      </div>
    </div>
  </page-wrapper>
</template>

<script>
import pageWrapper from '~/components/page-wrapper.vue'
export default {
  name: 'TechnicalSponsorTeam',
  components: { pageWrapper },
  data() {
    return {
      committee: [
        {
          img: require('assets/images/geetam.png'),
          desig: 'Section Chair',
          name: 'Dr. Geetam Tomar',
        },
        {
          img: require('assets/images/Manish-Dixit.png'),
          desig: 'Section Vice Chair, Operations',
          name: 'Dr. Manish Dixit',
        },
        {
          img: require('assets/images/narendra-chaudhari.png'),
          desig: 'Section Vice Chair, Liaison',
          name: 'Dr. Narendra Chaudhari',
        },
        {
          img: require('assets/images/amit_ojha.png'),
          desig: 'Section Secretary',
          name: 'Dr. Amit Ojha',
          email: '',
        },
        {
          img: require('assets/images/vk.png'),
          desig: 'Chair Newsletter',
          name: 'Dr. Vivek Tiwari',
          email: '',
        },
        {
          img: '',
          desig: 'TPAC Chair and Coordinator-CG',
          name: 'Dr. R.N. Patel',
          email: '',
        },
      ],
    }
  },
  head: {
    title:
      'Technical Sponsor Committee | OPJU International Technology Conference | 2022',
  },
}
</script>

<style>
.nav-link:hover {
  color: #3a86ff;
}

.o-card-container {
  margin-top: 3rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-start;
}

.o-card {
  padding: 1rem;
  width: 17rem;
  box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
  word-wrap: break-word;
  margin: 0 1rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.o-card-img {
  width: 80%;
  padding-bottom: 1rem;
  filter: grayscale(1);
}

#email-id {
  word-break: break-all;
}

@media (max-width: 768px) {
  .o-card-container {
    justify-content: center;
  }
  .o-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
}
</style>
