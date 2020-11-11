<template>
  <div>
    <!-- <img alt="Hero Image" v-bind:src="require(img[0].src)" class="img-hero1" /> -->
    <img alt="Hero Image" src="../assets/images/desktop-image-hero-1.jpg" class="img-hero1" />
  </div>
</template>

<script>
export default {
  name: "heroImage",
  data() {
    return {
      img: [
        {
          src: "../assets/images/desktop-image-hero-1.jpg"
        },
        {
          src: "../assets/images/desktop-image-hero-2.jpg"
        },
        {
          src: "../assets/images/desktop-image-hero-3.jpg"
        }
      ]
    };
  }
};
</script>

<style></style>
