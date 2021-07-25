<template>
  <div>
    <div
      class="d-flex justify-content-center align-items-center mb-1"
      id="header"
    >
      <p class="fw-bold m-1">Portfolio</p>
    </div>
    <general></general>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 150 1440 150">
      <path
        fill="#404040"
        fill-opacity="1"
        d="M0,224L60,240C120,256,240,288,360,277.3C480,267,600,213,720,186.7C840,160,960,160,1080,181.3C1200,203,1320,245,1380,266.7L1440,288L1440,0L1380,0C1320,0,1200,0,1080,0C960,0,840,0,720,0C600,0,480,0,360,0C240,0,120,0,60,0L0,0Z"
      ></path>
    </svg>
    <information></information>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 250">
      <path
        fill="#404040"
        fill-opacity="1"
        d="M0,32L34.3,58.7C68.6,85,137,139,206,176C274.3,213,343,235,411,218.7C480,203,549,149,617,112C685.7,75,754,53,823,42.7C891.4,32,960,32,1029,64C1097.1,96,1166,160,1234,154.7C1302.9,149,1371,75,1406,37.3L1440,0L1440,320L1405.7,320C1371.4,320,1303,320,1234,320C1165.7,320,1097,320,1029,320C960,320,891,320,823,320C754.3,320,686,320,617,320C548.6,320,480,320,411,320C342.9,320,274,320,206,320C137.1,320,69,320,34,320L0,320Z"
      ></path>
    </svg>
  </div>
</template>

<script>
import General from "@/components/General.vue";
import Information from "@/components/Information.vue";
export default {
  components: {
    general: General,
    information: Information,
  },
};
</script>
<style scoped>
#header {
  font-size: 6em;
  color: white;
  background-color: #323232;
}
</style>
