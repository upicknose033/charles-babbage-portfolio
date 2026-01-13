<template>
  <Navbar />
  <div class = "container-fluid">
    <About />
    <Projects />
    <Tools />
    <Contacts />
    <FooterComponent />
  </div>
</template>


<script setup>
  import  Navbar from './components/Navbar.vue';
  import About from './components/About.vue';
  import Projects from './components/Projects.vue';
  import Tools from './components/Tools.vue';
  import Contacts from './components/Contacts.vue';
  import FooterComponent from './components/FooterComponent.vue'
</script>