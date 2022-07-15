<template>
  <VKHeader />
  <VKContent />
  <footer>
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
@import url("https://fonts.googleapis.com/css2?family=Averia+Serif+Libre:wght@400&family=Fira+Sans:wght@300&family=Meow+Script&display=swap");
@import "./assets/reset.scss";
@import "./assets/core.scss";
@import "./assets/grid.scss";

body {
  background-image: url("./assets/ferns.jpg");
  // background-size: cover;
  background-repeat: repeat;

  a {
    color: #e9bcb7;
  }
}

body,
#app {
  margin: 0;
  padding: 0;
  min-height: 100vh;
  min-width: 100vw;
  max-width: 100vw;
  overflow-x: hidden;
  font-size: 16px;
  position: relative;
}

#app {
  font-family: "Fira Sans", Helvetica, sans-serif;
  font-family: "Averia Serif Libre", Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: $text-color;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
}
</style>
