<script>
import headerApp from './components/headerApp.vue';
import mainApp from './components/mainApp.vue';
import sectionMainApp from './components/sectionMainApp.vue';
import latestSectionMain from './components/latestSectionMain.vue';
import footerApp from './components/footerApp.vue'
import '@fortawesome/fontawesome-free/css/all.css';
import 'bootstrap/dist/css/bootstrap.css'



export default {
  components: {
    headerApp,
    mainApp,
    sectionMainApp,
    latestSectionMain,
    footerApp,

  },
  return: {

  },
};

</script>

<template>

  <headerApp />
  <mainApp />
  <sectionMainApp />
  <latestSectionMain />
  <footerApp />

</template>
<style></style>
