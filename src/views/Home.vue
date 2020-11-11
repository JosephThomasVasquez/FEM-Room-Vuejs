<template>
  <div class="home">
    <div class="section-main">
      <div class="img-container">
        <HeroImage />
      </div>
      <div class="section-headline">
        <div class="container-headline">
          <HeadlineContent />
          <div class="link-shop">
            <a href="/shop">SHOP NOW</a>
            <img
              src="../assets/images/icon-arrow.svg"
              alt="icon-arrow"
              class="icon-arrow"
            />
          </div>
        </div>
      </div>
    </div>
    <div class="section-bottom">
      <div class="bottm-left image-container">
        <img
          alt="Hero Image"
          src="../assets/images/image-about-dark.jpg"
          class="img-about-left"
        />
      </div>
      <div class="bottm-infotext">
        <h3 class="headline-h3">About our furniture</h3>
        <p class="headline-subtext">
          Our multifunctional collection blends design and function to suit your
          individual taste. Make each room unique, or pick a cohesive theme that
          best express your interests and what inspires you. Find the furniture
          pieces you need, from traditional to contemporary styles or anything
          in between. Product specialists are available to help you create your
          dream space.
        </p>
      </div>
      <div class="bottm-right image-container">
        <img
          alt="Hero Image"
          src="../assets/images/image-about-light.jpg"
          class="img-about-right"
        />
      </div>
    </div>
  </div>
</template>

<script>
import HeadlineContent from "@/components/HeadlineContent.vue";
import HeroImage from "@/components/HeroImage.vue";

export default {
  name: "Home",
  components: {
    HeadlineContent,
    HeroImage,
  },
};
</script>

<style scoped>
.section-bottom {
  position: absolute;
  display: grid;

  grid-template-columns: [bottomL] 32% [bottomM] 36% [bottomR] 32%;
  grid-template-rows: 100%;
  grid-template-areas: "imageL info imageR";
  overflow: hidden;
  bottom: 0;
  left: 0px;
  width: 100%;
  padding: 0;
  margin: 0;
}

.bottom-infotext {
  position: relative;
  width: 100%;
  margin: 0 10%;
}

.headline-h3 {
  grid-area: info;
  width: 100%;
  object-fit: contain;
}

.bottm-left,
.bottom-right {
  padding: 0;
  margin: 0;
  grid-area: imageL;
  width: 100%;
  object-fit: contain;
  border: 3px solid red;
}

.img-about-left {
  max-width: 60vw;
  height: auto;
}

.img-about-right {
  grid-area: imageR;
  max-width: 100%;
  height: auto;
  object-fit: contain;
}
</style>
