<template>
  <div class="home">
    <div class="img-container">
      <img
        alt="Vue logo"
        src="../../public\images\desktop-image-hero-1.jpg"
        class="img-hero1"
      />
      <HelloWorld msg="Room" />
    </div>
    <div class="section-headline">
      <div class="container-headline">
        <h1 class="headline-h1">Discover innovative ways to decorate</h1>
        <p class="headline-subtext">
          We provide unmatched quality, comfort, and style for property owners
          across the country. Our experts combine form andnfunction in bringing
          your vision to life. Create a room in your own style with our
          collection and make your property a reflection of you and what you
          love.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>
