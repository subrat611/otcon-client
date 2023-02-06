<template>
  <div>
    <page-header>
      <h2 class="">Keynote Speaker</h2>
    </page-header>
    <div class="container mt-4 py-4">
      <div class="row">
        <div class="col-lg-12 col-sm-12">
          <div class="col-lg-12 col-sm-12">
            <div class="o-card-container">
              <div
                v-for="({ member, Column2 }, i) in keyNoteSpeakers"
                :key="i"
                class="o-card mb-3"
              >
                <!-- <img :src="img" alt="img" class="o-card-img p-0 mb-3" /> -->
                <p class="m-0">{{ member }}</p>
                <h6 class="m-0 text-danger">{{ Column2 }}</h6>
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
  name: 'KeyNotePage',
  data() {
    return {
      keyNoteSpeakers: [
        {
          member: 'Dr. Ram Bilas Pachori',
          Column2: 'Professor, IIT Indore',
        },
        {
          member: 'Dr. Suraj Sharma',
          Column2:
            'Associate Professor, Guru Ghasidas Vishwavidyalaya A Central University Bilaspur',
        },
        {
          member: 'Dr. Dilip Singh Sisodia',
          Column2: 'Associate Professor, NIT Raipur',
        },
        {
          member: 'Dr. Thinagaran Perumal',
          Column2:
            'Associate Professor, Faculty of Computer Science and Information Technology, Universiti Putra Malaysia 43400',
        },
        {
          member: 'Dr. Tanupriya Choudhuty',
          Column2:
            'Sr. Associate Professor, University of Petroleum and Energy Studies, Dehradun, INDIA',
        },
        {
          member: 'Dr. Surbhi Bhatia,',
          Column2: 'Associate Professor, King Faisal University, Saudi Arebia',
        },
        {
          member: 'Dr. Manish Kumar Bajpai',
          Column2: 'Assistant Professor, III TDM, Jabalpur',
        },
      ],
    }
  },
  head: {
    title: 'Keynote Speaker | OPJU International Technology Conference | 2022',
  },
}
</script>

<style scoped>
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

@media (max-width: 768px) {
  .o-card-container {
    justify-content: center;
  }
  .o-card {
    width: 15rem;
  }
}
</style>
