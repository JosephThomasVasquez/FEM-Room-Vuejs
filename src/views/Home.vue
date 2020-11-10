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
      <h1>Discover innovative ways to decorate</h1>
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
