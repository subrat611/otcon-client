<template>
  <page-wrapper>
    <page-header>
      <h2 class="">Advisory Board</h2>
    </page-header>
    <div class="container mt-4 py-4">
      <div class="row">
        <div class="col-lg-12 col-sm-12">
          <h1 class="text-center my-5">International Advisory Board Members</h1>
          <div class="o-card-container">
            <div
              v-for="({ member, Column2 }, i) in advisoryBoardMember"
              :key="i"
              class="o-card mb-3"
            >
              <!-- <img :src="img" alt="img" class="o-card-img p-0 mb-3" /> -->
              <p class="m-0">{{ member }}</p>
              <h6 class="m-0 text-danger">{{ Column2 }}</h6>
            </div>
          </div>
        </div>
        <div class="col-lg-12 col-sm-12">
          <h1 class="text-center my-5">National Advisory Board Members</h1>
          <div class="o-card-container">
            <div
              v-for="({ member, Column2 }, i) in nationalAdvisoryBoardMember"
              :key="i"
              class="o-card mb-3"
            >
              <!-- <img :src="img" alt="img" class="o-card-img p-0 mb-3" /> -->
              <p class="m-0">{{ member }}</p>
              <h6 class="m-0 text-danger">{{ Column2 }}</h6>
            </div>
          </div>
        </div>
        <div class="col-lg-12 col-sm-12">
          <h1 class="text-center my-5">Scientific Program Committee</h1>
          <div class="o-card-container">
            <div
              v-for="({ member }, i) in scientificCommittee"
              :key="i"
              class="o-card mb-3"
            >
              <p class="m-0">{{ member }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </page-wrapper>
</template>

<script>
export default {
  name: 'AdvisoryBoardPage',
  data() {
    return {
      advisoryBoardMember: [
        {
          member: 'Dr. Bhupesh Kumar Singh',
          Column2: 'Arba Minch University, Ethopia',
        },
        {
          member: 'Dr. Surbhi Bhatia',
          Column2: 'King Faisal University, Saudi Arebia',
        },
        {
          member: 'Dr. Arun Somani',
          Column2: 'Dean Research, Iowa State University, , USA',
        },
        {
          member: 'Dr. Barry Winn',
          Column2: 'Vice-Chancellor, Sohar University, Oman',
        },
        {
          member: 'Dr. Mamun Bin IbneReaz',
          Column2: 'Professor, Universiti Kebangsaan Malaysia',
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
          member: 'Dr Umashankar Subramaniam',
          Column2:
            'Associate Professor, Prince Sultan University, Saudi Arabia',
        },
        {
          member: 'Daniel Braley',
          Column2: 'Associate Technical Fellow, Boeing',
        },
        {
          member: 'Dr Ashutosh Dutta',
          Column2:
            'Chief Scientist, Chief 5G Strategiest, Professor at John Hopkins University, Maryland',
        },
        {
          member: 'Dr Shlomi Dolev',
          Column2:
            'Rita Altura Chair Professor, Ben Gurion University of Negev',
        },
        {
          member: 'Prof. (Dr.) Almoataz Y. Abdelaziz',
          Column2: 'Future University Egypt',
        },
        {
          member: 'Dr. Felipe V. Lopes',
          Column2: 'Universidade Federal da Paraíba, Brazil',
        },
        {
          member: 'Dr Ernesto Mininno',
          Column2: 'Founder and CEO at Cyber Dyne srl, Italy',
        },
        {
          member: 'Dr Giovanni Iacca',
          Column2: 'Associate Professor at University of Trento, Italy ',
        },
        {
          member: 'Mr Tyler Garrett',
          Column2: 'dev3lop.com, USA',
        },
        {
          member: 'Mr Edouard Moens de Hase',
          Column2: 'Co-Founder and Managing Director at Aerosint, Belgium',
        },
        {
          member: 'Dr Nikolay Tontchev',
          Column2: 'University of Transport in Sofia, Bulgaria',
        },
        {
          member: 'Dr Hassan Haes Alhelou',
          Column2: 'Monash University, Australia',
        },
        {
          member: 'Dr Naayagi Ramasamy',
          Column2: 'Newcastle University, Singapore',
        },
        {
          member: 'Dr. Elena Zakharova',
          Column2: 'Ryazan State Radio Engineering University, Russia',
        },
        {
          member: 'Dr. Stanislav Goll',
          Column2: 'Ryazan State Radio Engineering University, Russia',
        },
      ],
      nationalAdvisoryBoardMember: [
        {
          member: 'Dr. Suraj Sharma',
          Column2: 'Guru Ghasidas Central University, Bilaspur, India',
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
          member: 'Dr. Preeti Sirohi',
          Column2: 'Senior Data Miner, Global Analytic, Concentrix',
        },
        {
          member: 'Dr. Ram Kishan Dewangan',
          Column2: 'Thapar Institute of Engineering and Technology, Patiyala',
        },
        {
          member: 'Dr. Tanupriya Choudhury',
          Column2: 'University of Petroleum and Energy Studies, Dehradun',
        },
        {
          member: 'Dr. Deepak Dewangan',
          Column2: 'Thapar Institute of Engineering and Technology, Patiyala',
        },
        {
          member: 'Dr. Monika Arya',
          Column2: 'Bhilai Institue of Technology, Durg',
        },
        {
          member: 'Dr. TP Singh',
          Column2: 'University of Petroleum and Energy Studies, Dehradun',
        },
        {
          member: 'Dr. Amitava Choudhury',
          Column2: 'Pandit Deendayal Energy University, Ahamdabad',
        },
        {
          member: 'Dr. Asha Abhyankar',
          Column2: 'Kalinga University, Raipur',
        },
        {
          member: 'Dr. Gunjan Chhabra',
          Column2: 'Graphic Era University, Dehradun',
        },
        {
          member: 'Dr. Sumit Agrawal',
          Column2: 'Thapar Institute of Engineering and Technology, Patiyala',
        },
        {
          member: 'Dr. Pardeep Mann',
          Column2: 'Graphic Era University, Dehradun',
        },
        {
          member: 'Dr. Tanmay Bhaumik',
          Column2: 'Pandit Deendayal Energy University, Ahamdabad',
        },
        {
          member: 'Dr Kiran Kumar Ravulakollu',
          Column2: 'Woxen University, Hyderabad',
        },
        {
          member: 'Dr. Ashish Tamrakar',
          Column2: 'RSR, Rungta College of Engineering and Technology, Bhilai',
        },
        {
          member: 'Dr. Narayan Krishnaswamy',
          Column2: 'Professor, Sai Vidya Institute of Technology, Bangalore',
        },
        {
          member: 'Dr Paawan Sharma',
          Column2: 'Associate Professor, Pandit Deendayal Energy University',
        },
        {
          member: 'Dr Anil Kumar Soni',
          Column2:
            'Assistant Professor, Guru Ghasidas Central University, Bilaspur, India',
        },
        {
          member: 'Dr. N. Vishwanathan',
          Column2: 'Head, R&amp;D, Jindal Steel and Power, Raigarh',
        },
        {
          member: 'Dr. Shuaib Ahmed',
          Column2:
            'Technical Manager (T5), Mercedes-Benz Research and Development India',
        },
        {
          member: 'Dr Bhupathi Muruganathan',
          Column2: 'Application Engineering Manager (Analytics) Honeywell',
        },
        {
          member: 'Dr Arjit Saha Poddar',
          Column2: 'Head, R &amp; D, Jindal Stainless Ltd. ( JSL)',
        },
        {
          member: 'Dr Arghya Majumder',
          Column2:
            'Director, School of Mines and Metallurgy, Kazi Nazrul University',
        },
        {
          member: 'Dr V S Rao',
          Column2: 'Vice Chancellor, SRM University, Amaravathi ',
        },
        {
          member: 'Dr. Ramkishor Anant\n',
          Column2: 'Assistant Professor, MANIT, Bhopal, Madhya Pradesh',
        },
        {
          member: 'Dr. Tikendra Verma',
          Column2: 'Assistant Professor, MANIT, Bhopal, Madhya Pradesh',
        },
        {
          member: 'Dr Gayadhar Panda',
          Column2: 'Dean and Professor, NIT Meghalaya',
        },
        {
          member: 'Dr Trapti Jain',
          Column2: 'IIT Indore',
        },
        {
          member: 'Dr Manish Kumar Bajpai',
          Column2: 'IIIT Jabalpur',
        },
        {
          member: 'Dr Koushlendra Kumar Singh',
          Column2: 'NIT Jamshedpur',
        },
        {
          member: 'Dr. Vijeta Khare',
          Column2:
            'School of Cyber Security and Digital Forensic, National Forensic Science University, Gandhinagar, Gujrat, India',
        },
        {
          member: 'Dr. Sudeepa Das',
          Column2:
            "Computer Science and Engineering, Vignan's Institute of Information Technology, Vishakhapatanam, A.P. India",
        },
      ],
      scientificCommittee: [
        {
          member: 'Dr. Rakesh Nayak',
        },
        {
          member: 'Dr. Bhupesh Kumar Dewangan',
        },
        {
          member: 'Dr. Saroj Chandra',
        },
        {
          member: 'Dr. Abhilasha Chaudhury',
        },
        {
          member: 'Dr. Gulshan Soni',
        },
        {
          member: 'Dr. Vinod Kumar',
        },
        {
          member: 'Dr. Sushree Diptimayee Swain',
        },
        {
          member: 'Prof. R.N. Shukla',
        },
        {
          member: 'Prof. Umashankar Pandey',
        },
        {
          member: 'Prof. Asimkiran Dandapat',
        },
        {
          member: 'Prof. Pradeep Shriwas',
        },
        {
          member: 'Prof. Princy Diwan',
        },
      ],
    }
  },
  head: {
    title: 'Advisory Board | OPJU International Technology Conference | 2022',
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
