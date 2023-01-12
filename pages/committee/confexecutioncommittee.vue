<template>
  <page-wrapper>
    <page-header>
      <h2 class="">Conference Execution Committee</h2>
    </page-header>
    <div class="container my-4 py-4">
      <div class="o-card-container">
        <div
          v-for="({ img, name, desig, email }, i) in committee"
          :key="i"
          class="o-card mb-3"
        >
          <img :src="img" alt="img" class="o-card-img p-0 mb-3" />
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
export default {
  name: 'ConfExecutionCommittee',
  data() {
    return {
      committee: [
        {
          img: null,
          desig: 'Incharge Registration',
          name: 'Mr. Asimkrian Dandapat',
          email: 'asimkiran.dandapat@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Certificate',
          name: 'Dr. Abhilasha Chaudhary',
          email: 'abhilasha.chaudhuri@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Technical Support',
          name: 'Mr. Parikshit Singh',
          email: 'parikshit@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Session Management(online)',
          name: 'Dr. Amit Jain  ',
          email: 'amit.jain@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Venue Preparation(offline)',
          name: 'Mr. Umashankar Pandey',
          email: 'umashankar.pandey@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Transportation',
          name: 'Mr. Pradeep Kumar Shriwas',
          email: 'pradeep.shriwas@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Conference Proceeding',
          name: 'Dr. Gulshan Soni',
          email: 'gulshan.soni@opju.ac.in ',
        },
        {
          img: null,
          desig: 'Incharge Media coverage and stage coordination',
          name: 'Dr. Sanjay Singh',
          email: 'sanjay.singh@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Photography, Videography',
          name: 'Mr. Anup Bharti',
          email: 'anup.bharti@opju.ac.in',
        },
        {
          img: null,
          desig:
            'Incharge invitation and plan of execution of inauguration and valedictory',
          name: 'Dr. Bhupesh Dewangan,',
          email: 'bhupesh.dewangan@opju.ac.in',
        },
        {
          img: null,
          desig:
            'Incharge invitation and plan of execution of inauguration and valedictory',
          name: 'Dr. Amit Jain',
          email: 'amit.jain@opju.ac.in',
        },
        {
          img: null,
          desig:
            'Incharge invitation and plan of execution of inauguration and valedictory',
          name: 'Prof. R N Shukla',
          email: 'rnshukla@opju.ac.in',
        },
        {
          img: null,
          desig:
            'Incharge invitation and plan of execution of inauguration and valedictory',
          name: 'Dr. Saroj Chandra',
          email: 'saroj.chandra@opju.ac.in',
        },
        {
          img: null,
          desig:
            'Incharge invitation and plan of execution of inauguration and valedictory',
          name: 'Mr. Babloo Raouth',
          email: 'babloo.routh@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Accommodation',
          name: 'Ms. Manju Yadav',
          email: 'manju.yadav@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Catering and Food',
          name: 'Prof. R N Shukla',
          email: 'rnshukla@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Conference Kit preparation and distribution',
          name: 'Mr. Asim',
          email: 'asimkiran.dandapat@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Conference Kit preparation and distribution',
          name: 'Prof. R N Shukla',
          email: 'rnshukla@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Conference Kit preparation and distribution',
          name: 'Dr. Bhupesh',
          email: 'bhupesh.dewangan@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Conference Kit preparation and distribution',
          name: 'Dr. Saroj',
          email: 'saroj.chandra@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Publication Chair IEEE Xplore',
          name: 'Dr. Rakesh Nayak',
          email: 'rakesh.nayak@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Core Committee',
          name: 'Dr. Bhupesh',
          email: 'bhupesh.dewangan@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Core Committee',
          name: 'Dr. Kalyan',
          email: 'kalyan.makkuva@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Core Committee',
          name: 'Dr. Saroj',
          email: 'saroj.chandra@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Core Committee',
          name: 'Dr. Rakesh Nayak',
          email: 'rakesh.nayak@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Core Committee',
          name: 'Dr. Amit Jain',
          email: 'amit.jain@opju.ac.in',
        },
        {
          img: null,
          desig: 'Incharge Core Committee',
          name: 'Prof RN Shukla',
          email: 'rnshukla@opju.ac.in',
        },
      ],
    }
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
