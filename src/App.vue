<template>
  <div id="app">
    <div id="nav">
      <div class="nav-bar">
        <div class="title-name">room</div>
        <router-link to="/">Home</router-link>
        <router-link to="/shop">Shop</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/contact">Contact</router-link>
      </div>
    </div>
    <router-view />
  </div>
</template>
