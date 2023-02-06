<template>
  <page-wrapper>
    <page-header>
      <h2>Members of OPJU IEEE Student Chapter</h2>
      <p class="text-light">
        OP Jindal University has a local IEEE Student chapter. The student
        members of this chapter are extending their support in organization of
        the OTCON conference.
      </p>
    </page-header>
    <div class="container my-4 py-4">
      <div class="o-card-container">
        <div
          v-for="({ name, branch }, i) in committee"
          :key="i"
          class="o-card mb-3"
        >
          <p class="m-0">{{ name }}</p>
          <h6 class="m-0 text-danger">IEEE Student Member ({{ branch }})</h6>
          <!-- <h6 class="mt-2 text-dark">
            {{ !email ? '' : 'Email:' }}<br />
            <a id="email-id" :href="'mailto:' + email">{{ email }}</a>
          </h6> -->
        </div>
      </div>
    </div>
  </page-wrapper>
</template>

<script>
export default {
  name: 'ExtendedSupportCommittee',
  data() {
    return {
      committee: [
        {
          img: require('assets/images/avtar.png'),
          name: 'Vedika Agrawal',
          mobNo: '8349910279',
          membershipNo: '97773940',
          email: 'vedi.ug19cse53@opju.ac.in',
          branch: 'CSE',
        },
        {
          img: require('assets/images/avtar.png'),
          name: 'Ritika Singh',
          mobNo: '6267425664',
          membershipNo: '97774708',
          email: 'riti02025@gmail.com',
          branch: 'CSE',
        },
        {
          img: require('assets/images/avtar.png'),
          name: 'Harsh Pandey',
          mobNo: '9630966243/8770721320',
          altno: '8770721320',
          membershipNo: '97775193',
          email: 'harshrajpandey.49@gmail.com',
          branch: 'EE',
        },
        {
          img: require('assets/images/avtar.png'),
          name: 'V.ujjwala',
          mobNo: '8982992201',
          membershipNo: '97773946',
          email: 'vungaralaujjwala2002@gmail.com',
          branch: 'EE',
        },
        {
          img: require('assets/images/avtar.png'),
          name: 'Utkarsh Dixit',
          mobNo: '7735886881',
          membershipNo: '97773964',
          email: 'utkarshdixit2021@gmail.com',
          branch: 'CSE',
        },
        {
          img: require('assets/images/avtar.png'),
          name: 'Monal Singh',
          mobNo: '9131901837',
          membershipNo: '97773934',
          email: 'monalsingh234@gmail.com',
          branch: 'CSE',
        },
        {
          img: require('assets/images/avtar.png'),
          name: 'Poonam Pandey',
          mobNo: '8085950108',
          membershipNo: '97775225',
          email: 'poonam.shukla@jindalpower.com',
          branch: 'CSE',
        },
        {
          img: require('assets/images/avtar.png'),
          name: 'Avaneesh Jha',
          mobNo: '7247279229',
          membershipNo: '96379447',
          email: 'vipavaneesh@gmail.com',
          branch: 'CSE',
        },
        {
          img: require('assets/images/avtar.png'),
          name: 'Shivam Kumar Jha',
          mobNo: '8271953137',
          membershipNo: '98266299',
          email: 'skjha0111@gmail.com',
          branch: 'EE',
        },
        {
          img: require('assets/images/avtar.png'),
          name: 'Abhineet Singh',
          mobNo: '9334257009',
          membershipNo: '98266267',
          email: 'abhineet9652@gmail.com',
          branch: 'EE',
        },
        {
          img: require('assets/images/avtar.png'),
          name: 'Shambhavi Awasthi',
          mobNo: '8827129702',
          membershipNo: '98227982',
          email: 'shambhavi030902@gmail.com',
          branch: 'CSE',
        },
        {
          img: require('assets/images/avtar.png'),
          name: 'Ambuj Raj',
          mobNo: '9546093830',
          membershipNo: '98228086',
          email: 'ambhujraj6400@gmail.com',
          branch: 'CSE',
        },
        {
          img: require('assets/images/avtar.png'),
          name: 'Suryanshu Dobai',
          mobNo: '7008575068',
          membershipNo: '98234195',
          email: 'suryanshudobai@gmail.com',
          branch: 'CSE',
        },
      ],
    }
  },
  head: {
    title:
      'Extended Support Committee | OPJU International Technology Conference | 2022',
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
