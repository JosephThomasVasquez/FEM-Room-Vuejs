<template>
  <div id="app">
    <div id="nav">
      <div class="title-name">Room</div>
      <router-link to="/">Home</router-link> |
      <router-link to="/shop">Shop</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/contact">Contact</router-link>
    </div>
    <router-view />
  </div>
</template>