<script>

</script>

<template>
  <header>
    <div id="header">
      <div id="header_logo">
        <img src="./assets/Logo.png" alt="Logo ShutterSpecht"/>
        <a class="link" href="#">
          <h1 id="logo_name">ShutterSpecht</h1>
        </a>
      </div>
      <nav class="header_nav">
        <button @click="menu_function()" class="header_nav__btn" aria-label="Menu">☰</button>
        <ul class="header_nav__ul">
          <li class="header_nav__li">
            <a href="#service" class="link header_nav__link">Services</a>
          </li>
          <li class="header_nav__li">
            <a href="#section_gallery" class="link header_nav__link">Gallery</a>
          </li>
          <li class="header_nav__li header_nav__li--desktop">
            <a href="#section_contact" class="link header_nav__link">Book now</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
  <section id="section_service">
    <div id="platzhalter"></div>
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

  <section id="section_event">
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

  <section id="section_gallery">
    <div class="container">
      <h2 class="section_heading section_heading--gallery">Gallery</h2>
      <div class="flexbox flexbox--gallery">
        <div class="upper_flexbox">
          <div class="gallery_box">
            <img class="box_image box_image--protrait" src="./assets/pictures/personal.jpg" alt="Gallery-Image Portrait" />
              <h4 class="box_heading box_heading--gallery">Portrait</h4>
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

  
  <section id="section_contact">
    <div class="container">
      <div class="flexbox flexbox--frm">
        <div class="content_left">
          <h4 class="frm_heading">Jetzt Termin sichern!</h4>
          <p class="frm_text">
            Einfach das Formular ausfüllen, 
            Wunsch-Termin auswählen und ich 
            werde mich schnellstmöglich mit 
            dir in Verbindung setzen. 
          </p>
        </div>
        <div class="content_right">
          <form class="form" action="#" methode="GET">
            <div class="form_input_container">
              <input class="form_input" type="text" name="name" placeholder="Dein Name...">
            </div>
            <div class="form_input_container">
              <input class="form_input" type="email" name="email" placeholder="Deine E-Mail-Adresse...">
            </div>
            <div class="form_input_container">
              <input class="form_input" type="text" name="phone" placeholder="Deine Handynummer...">
            </div>
            <div class="form_input_container">
              <input class="form_input" type="text" name="date" placeholder="Gewünschter Termin...">
            </div>
            <div class="form_input_container">
              <textarea class="form_textarea" placeholder="Deine Nachricht..."></textarea>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>

</template>

<script lang="js">
  export default {
    methods: {
      menu_function() {
        console.log("Test");
        const menu = document.querySelector('.header_nav__ul');
        menu.classList.toggle('open');
      }
    }
  };
</script>