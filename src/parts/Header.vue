<template>
  <header>
    <div class="header-contents">
      <h1 class="animate__animated animate__fadeInUp">Valerie Kraucunas</h1>
      <!-- <h1 class="">Valerie Kraucunas</h1> -->
      <div class="flex-row link-row animate__animated animate__fadeIn">
        <a href="./VK_Resume.pdf" target="_blank"
          ><p>resum<span>e</span></p></a
        >
        <a href="#" target="_blank"
          ><p>githu<span>b</span></p></a
        >
        <a href="#" target="_blank"
          ><p>linkedi<span>n</span></p></a
        >
      </div>
      <img src="../../public/me.gif" />
    </div>
  </header>
</template>

<script>
export default {
  name: "VKHeader",
};
</script>

<style lang="scss">
@import "../assets/animate.scss";

header {
  width: 100vw;
  position: relative;
  padding: 6rem;
  height: 30vh;
  min-height: 80vh;
  background-color: rgba(13, 58, 45, 0.4);

  .header-contents {
    width: 90%;
    margin: 10rem auto 0;
    text-align: center;
    width: 100%;
    position: relative;

    img {
      height: auto;
      max-height: 400px;
    }

    h1 {
      animation: fadeInUp;
      animation-duration: 1.35s;
      animation-delay: 0.25s;
      font-family: "Meow Script", Helvetica, sans-serif;
      font-size: 4rem;
      font-weight: 400;
      margin-bottom: 5rem;
    }

    .link-row {
      animation: fadeIn;
      animation-duration: 3s;
      width: 50%;
      margin: 0 auto;
      a {
        color: #e9bcb7;
        font-variant: small-caps;
        letter-spacing: 8px;
        font-size: 1.5rem;

        span {
          letter-spacing: normal;
        }
      }
    }

    @media screen and (min-width: 600px) {
      h1 {
        font-size: 6rem;
      }
    }
  }
}
</style>
