<script>
import headerApp from './components/headerApp.vue';
import mainApp from './components/mainApp.vue';
import sectionMainApp from './components/sectionMainApp.vue';
import '@fortawesome/fontawesome-free/css/all.css';
import 'bootstrap/dist/css/bootstrap.css'



export default {
  components: {
    headerApp,
    mainApp,
    sectionMainApp,

  },
  return: {

  },
};

</script>

<template>

  <headerApp />
  <mainApp />
  <sectionMainApp />

</template>
<style></style>
