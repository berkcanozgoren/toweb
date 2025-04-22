<template>
  <div class="edrea_tm_section" id="about">
    <div class="section_inner">
      <div class="edrea_tm_about">
        <div class="left">
          <div class="image">
            <img src="img/thumbs/1-1.jpg" alt="" />
            <div class="main" data-img-url="img/about/1.jpg"></div>
          </div>
        </div>
        <div class="right">
          <div class="short">
            <h3 class="name">HOW WE <span class="coloring">TAKE OFF?</span></h3>
            <h3 class="job">
              <AnimationText />
            </h3>
          </div>
          <div class="text">
            <p> 
              Take Off is a gateway to the darker side of electronic music.  
              We design high-intensity nights inside raw, industrial spaces — where sharp lights cut through fog and BPMs never fall below the line.  
              Every event is engineered with precision — from the stage build to the sound system.  
              This isn’t a show. It’s an experience.  
              Don’t just attend.  
              Take Off is meant to be felt.
            </p>
          </div>
          <div class="edrea_tm_button" id="aboutPopup">
            <a href="#">Learn More</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import AnimationText from "./AnimationText.vue";
export default {
  name: `AboutComponent`,
  data() {
    return {
      open: false,
    };
  },
  components: {
    AnimationText,
  },
};
</script>

<style scoped>
.edrea_tm_modalbox {
  top: -90px;
}
</style>
