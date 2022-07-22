<template>
  <VKHeader />
  <VKContent />
  <footer>
    <div class="link-row">
      <a href="./VK_Resume.pdf" target="_blank">resum<span>e</span></a>
      <a href="#" target="_blank">githu<span>b</span></a>
      <a href="#" target="_blank">linkedi<span>n</span></a>
    </div>
    <p>&copy; {{ new Date().getFullYear() }}, Valerie Kraucunas</p>
  </footer>
</template>

<script>
import VKHeader from "./parts/Header.vue";
import VKContent from "./parts/Content.vue";

export default {
  name: "App",
  components: {
    VKHeader,
    VKContent,
  },
};
</script>

<style lang="scss">
@import "./assets/reset.scss";
@import "./assets/core.scss";

body {
  background-image: url("./assets/cacti.jpg");
  background-size: cover;
}

#app {
  font-family: "Averia Serif Libre", Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: $text-color;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;

  footer {
    width: 100vw;
    margin-bottom: 2rem;

    .link-row {
      margin-bottom: 2rem;
    }
  }
}
</style>
