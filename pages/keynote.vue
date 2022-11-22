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
          member: 'Dr. Surbhi Bhatia',
          Column2: 'King Faisal University, Saudi Arebia',
        },
        {
          member: 'Dr. Christian Blum',
          Column2:
            'Senior Research Scientist, Artificial Intelligence Research Institute (IIIA), Spain',
        },
        {
          member: 'Dr. Cynthia Furse',
          Column2:
            'Professor, University of Utah, Co-Founder Live Wire Innovation, USA',
        },
        {
          member: 'Dr. Ravi Prakash',
          Column2: 'Professor, University of Texas Dallas, USA',
        },
        {
          member: 'Dr. Marcin PAPRZYCKI',
          Column2: 'Professor, Polish Academy of Sciences, Poland',
        },
        {
          member: 'Dr. Chandraprakash Bhujetiya',
          Column2: 'NIT Delhi',
        },
        {
          member: 'Dr Ravi Tomar',
          Column2: 'Senior Architect, Persistent Systems Ltd., India',
        },
        {
          member: 'Dr V S Rao',
          Column2: 'Vice Chancellor, SRM University, Amaravathi ',
        },
        {
          member: 'Dr Gayadhar Panda',
          Column2: 'Dean and Professor, NIT Meghalaya',
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