<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <div id="header">
      <img id="logo" src="./assets/Logo.png" alt="Logo ShutterSpecht"/>
      <h1 id="logo_name">ShutterSpecht</h1>
    </div>
  </header>
  <section id="service_content">
    <div id="service">
      <div class="container">
        <h2 class="section_heading">Service ist alles</h2>
        
        <div class="flexbox">
          <div class="service_box">
            <img class="box_image image__weeding" src="./assets/pictures/wedding.jpg" alt="Image 1 Service"/>
            <h4 class="box_heading">Wedding</h4>
          </div>
          <div class="service_box">
            <img class="box_image image__events" src="./assets/pictures/events.jpg" alt="Image 2 Service"/>
            <h4 class="box_heading">Events</h4>
          </div>
          <div class="service_box">
            <img class="box_image image__personal" src="./assets/pictures/personal.jpg" alt="Image 3 Service"/>
            <h4 class="box_heading">Personal</h4>
          </div>
        </div>
      </div> 
    </div>
  </section>

  <section id="event_content">
    <div class="container">
      <div class="event_description">
        <h2 class="heading_event">
          <span class="heading_event heading_small">Der beste Ansprechpartner<br /></span>
          Für jedes Event
        </h2>
        <p class="event_p">
          Hier ein bisschen bla bla 
          und so und natürlich noch 
          ein anderes Hintergrundbild
        </p>
      </div>
    </div>
  </section>

  <section id="gallery_content">
    <div class="container">
      <h2 class="section_heading section_heading--gallery">Gallery</h2>
      <div class="flexbox flexbox--gallery">
        <div class="upper_flexbox">
          <div class="gallery_box">
            <img class="box_image box_image--protrait" src="./assets/pictures/personal.jpg" alt="Gallery-Image Portrait" />
            <div class="box_heading box_heading--gallery">
              <h4 class="">Portrait</h4>
            </div>
          </div>
          <div class="gallery_box">
            <img class="box_image box_image--wedding" src="./assets/pictures/wedding.jpg" alt="Gallery-Image Wedding" />
            <h4 class="box_heading box_heading--gallery">Wedding</h4>
          </div>
          <div class="gallery_box">
            <img class="box_image box_image--event" src="./assets/pictures/events.jpg" alt="Gallery-Image Event" />
            <h4 class="box_heading box_heading--gallery">Event</h4>
          </div>
        </div>
        <div class="lower_flexbox">
          <div class="gallery_box">
            <img class="box_image box_image--wildlife" src="./assets/pictures/wildlife.jpg" alt="Gallery-Image Wildlife" />
            <h4 class="box_heading box_heading--gallery">Wildlife</h4>
          </div>
          <div class="gallery_box">
            <img class="box_image box_image--street" src="./assets/pictures/street.jpg" alt="Gallery-Image Street" />
            <h4 class="box_heading box_heading--gallery">Street</h4>
          </div>
        </div>
      </div>
    </div>
  </section>

</template>

<style>

</style>
