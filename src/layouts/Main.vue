<template>
  <div class="main">
    <div class="logo">
        <div class="logo-header">nconrad</div>
        <div class="logo-subtext">
            <span class="blue">UI Developer</span> . <span class="blue">Musician</span> . <span class="blue">Taco Scientist</span>
        </div>
    </div>

    <div class="nav">

        <v-link href="/about" title="" class="about-btn">
          <i class="typcn typcn-info-large-outline"></i>
          <span class="text">About</span>
        </v-link>


        <v-link href="/work" title="" class="work-btn">
          <i class="typcn typcn-briefcase"></i>
          <span class="text">Work</span>
        </v-link>


        <v-link href="/music" title="" class="music-btn">
          <i class="typcn typcn-notes-outline"></i>
         <span class="text">Music</span>
        </v-link>


        <v-link href="/contact" title="" class="contact-btn">
          <i class="typcn typcn-mail"></i>
          <span class="text">Contact</span>
        </v-link>

      <!--
      <v-link class="social" href="http://www.linkedin.com/pub/neal-conrad/14/370/b5b">
          <img src="img/social/linkedin.png" />
      </v-link>
      <v-link class="social" href="https://www.facebook.com/neal.conrad">
          <img src="img/social/facebook.png" />
      </v-link>
      -->
    </div>

    <slot></slot>
  </div>
</template>

<script>
  import VLink from '../components/VLink.vue'

  export default {
    components: {
      VLink
    }
  }
</script>

<style src="../assets/css/style.css">





</style>
