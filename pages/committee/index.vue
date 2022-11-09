<template>
  <page-wrapper>
    <page-header>
      <h2 class="">Organizing Committe</h2>
    </page-header>
    <div class="container my-4 py-4">
      <div class="o-card-container">
        <div class="o-card" v-for="({name, desig}, i) in committee" :key="i">
          <img
            src="https://d2975dej41kw79.cloudfront.net/jgu/wp-content/uploads/20220131070136/naveen-1.png"
            alt="img"
            class="o-card-img p-0 mb-3"
          />
          <p class="m-0">{{name}}</p>
          <h6 class="m-0 text-danger">{{desig}}</h6>
        </div>
      </div>
    </div>
  </page-wrapper>
</template>

<script>
import pageWrapper from '~/components/page-wrapper.vue'
export default {
  components: { pageWrapper },
  name: 'IndexPage',
  data() {
    return {
      committee: [
        {
          desig: 'Chief Patron',
          name: 'Mr. Naveen Jindal',
        },
        {
          desig: 'Patron',
          name: 'Ms. Shallu Jindal',
        },
        {
          desig: 'Chairman',
          name: 'Dr. R.D. Patidar',
        },
        {
          desig: 'General Chair',
          name: 'Dr. Ashok Bhansali (Nominated by IEEE MP Section)',
        },
        {
          desig: 'Convener',
          name: 'Dr. Bhupesh Kumar Dewangan',
        },
        {
          desig: 'Convener',
          name: 'Dr. Kalyan Phani',
        },
        {
          desig: 'Co-Convener',
          name: 'Dr. B.P. Panda',
        },
        {
          desig: 'Co-Convener',
          name: 'Dr. Sandeep Biswal',
        },
        {
          desig: 'Organizing Secretaries',
          name: 'Dr. Nitesh Bharadwaj',
        },
        {
          desig: 'Organizing Secretaries',
          name: 'Dr. Satish Kanhed',
        },
        {
          desig: 'Joint Secretaries',
          name: 'Dr. Rajesh Jha',
        },
        {
          desig: 'Joint Secretaries',
          name: 'Dr. Sushree Diptimayee Swain',
        },
        {
          desig: 'Technical Program Chair',
          name: 'Dr. Saroj Chandra',
        },
        {
          desig: 'Publication Chair',
          name: 'Dr. Rakesh Nayak',
        },
        {
          desig: 'Publicity Chair',
          name: 'Dr. Sanjay Singh / Mr. Anup Kumar Bharti',
        },
        {
          desig: 'Finance Chair',
          name: 'Mr. Siddhant Chaturvedi',
        },
        {
          desig: 'Web Chair',
          name: 'Dr. Abhilasha Chaudhuri',
        },
      ],
    }
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
  justify-content: center;
}

.o-card {
  padding: 1rem;
  width: 15rem;
  margin: 0 1rem;
}

.o-card-img {
  width: 10rem;
  padding-bottom: 1rem;
  filter: grayscale(1);
}

/* mobile 

.o-card {
  width: 10rem;
  margin: 0 1rem;
}

.o-card-img {
  width: 8rem;
}

*/
</style>