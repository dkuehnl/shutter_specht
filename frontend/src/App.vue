<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <div id="header">
      <img id="logo" src="./assets/Logo.png" alt="Logo ShutterSpecht"/>
      <p id="logo_name">ShutterSpecht</p>
    </div>
  </header>
  <section id="service_content">
    <div id="service">
      <div class="container">
        <h2 id="heading_service">Service ist alles</h2>
        
        <div class="flexbox">
          <div class="service_box">
            <img class="service_box_image" src="./assets/pictures/wedding.jpg" alt="Image 1 Service"/>
            <h4 class="service_box_heading">Wedding</h4>
          </div>
          <div class="service_box">
            <img class="service_box_image" src="./assets/pictures/events.jpg" alt="Image 2 Service"/>
            <h4 class="service_box_heading">Events</h4>
          </div>
          <div class="service_box">
            <img class="service_box_image" src="./assets/pictures/personal.jpg" alt="Image 3 Service"/>
            <h4 class="service_box_heading">Personal</h4>
          </div>
        </div>
      </div> 
    </div>
  </section>

</template>

<style scoped>

</style>
