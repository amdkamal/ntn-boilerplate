<template>
  <header>
    <nuxt-link to="/"> <h1 class="logo">Ahmed Kamal</h1></nuxt-link>
    <nav class="nav">
      <ul>
        <!-- <li><nuxt-link to="/#">about</nuxt-link></li> -->
        <li><nuxt-link to="/#projects">projects</nuxt-link></li>
        <li><nuxt-link to="/#contact">contact</nuxt-link></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  methods: {
    navToggle() {
      let menu = document.querySelector("header");
      let stuff = document.querySelector(".content");
      menu.classList.toggle("active");
      stuff.classList.toggle("menu-active");
    },
    closeMenu() {
      let menu = document.querySelector("header");
      let stuff = document.querySelector(".content");
      menu.classList.remove("active");
      stuff.classList.remove("menu-active");
    },
  },
};
</script>

<style></style>
