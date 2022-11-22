<template>
  <page-wrapper>
    <page-header>
      <h2 class="">Organizing Committe</h2>
    </page-header>
    <div class="container my-4 py-4">
      <div class="o-card-container">
        <div
          v-for="({ img, name, desig }, i) in committee"
          :key="i"
          class="o-card mb-3"
        >
          <img :src="img" alt="img" class="o-card-img p-0 mb-3" />
          <p class="m-0">{{ name }}</p>
          <h6 class="m-0 text-danger">{{ desig }}</h6>
        </div>
      </div>
    </div>
  </page-wrapper>
</template>

<script>
import pageWrapper from '~/components/page-wrapper.vue'
export default {
  name: 'IndexPage',
  components: { pageWrapper },
  data() {
    return {
      committee: [
        {
          img: require('assets/images/13.png'),
          desig: 'Chief Patron',
          name: 'Mr. Naveen Jindal',
        },
        {
          img: require('assets/images/10.png'),
          desig: 'Patron',
          name: 'Ms. Shallu Jindal',
        },
        {
          img: require('assets/images/12.png'),
          desig: 'Chairman',
          name: 'Dr. R.D. Patidar',
        },
        {
          img: require('assets/images/17.png'),
          desig: 'General Chair',
          name: 'Dr. Ashok Bhansali',
        },
        {
          img: require('assets/images/2.png'),
          desig: 'Convener',
          name: 'Dr. Bhupesh kr. Dewangan',
        },
        {
          img: require('assets/images/6.png'),
          desig: 'Convener',
          name: 'Dr. M. Kalyan Phani',
        },
        {
          img: require('assets/images/14.png'),
          desig: 'Co-Convener',
          name: 'Dr. B.P. Panda',
        },
        {
          img: require('assets/images/1.png'),
          desig: 'Co-Convener',
          name: 'Dr. Sandeep Biswal',
        },
        {
          img: require('assets/images/9.png'),
          desig: 'Organizing Secretaries',
          name: 'Dr. Satish Kanhed',
        },
        {
          img: require('assets/images/8.png'),
          desig: 'Joint Secretary',
          name: 'Dr. Rajesh Jha',
        },
        {
          img: require('assets/images/16.png'),
          desig: 'Joint Secretary',
          name: 'Dr. Sushree Diptimayee Swain',
        },
        {
          img: require('assets/images/5.png'),
          desig: 'Technical Program Chair',
          name: 'Dr. Saroj Chandra',
        },
        {
          img: require('assets/images/3.png'),
          desig: 'Publication Chair',
          name: 'Dr. Rakesh Nayak',
        },
        {
          img: require('assets/images/7.png'),
          desig: 'Publicity Chair',
          name: 'Dr. Sanjay Singh',
        },
        {
          img: require('assets/images/15.png'),
          desig: 'Publicity Chair',
          name: 'Mr. Anup Kumar Bharti',
        },
        {
          img: require('assets/images/4.png'),
          desig: 'Web Chair',
          name: 'Dr. Abhilasha Chaudhuri',
        },
        {
          img: '@/assets/images/1.png',
          desig: 'Finance Chair',
          name: 'Mr. Siddhant Chaturvedi',
        },
      ],
    }
  },
  head: {
    title:
      'Organizing Committe | OPJU International Technology Conference | 2022',
  },
}
</script>

<style scoped>
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
  margin: 0 1rem;
}

.o-card-img {
  width: 10rem;
  padding-bottom: 1rem;
  filter: grayscale(1);
}

@media (max-width: 768px) {
  .o-card-container {
    justify-content: center;
  }
  .o-card {
    width: 15rem;
  }
}
</style>