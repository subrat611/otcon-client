<template>
  <page-wrapper>
    <page-header>
      <h2 class="">Extended Support Committee</h2>
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
  name: 'ExtendedSupportCommittee',
  data() {
    return {
      committee: [],
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
