<template>
  <header>
    <h1>Valerie Kraucunas</h1>
    <div class="link-row">
      <a href="./VK_Resume.pdf" target="_blank">resum<span>e</span></a>
      <a href="#" target="_blank">githu<span>b</span></a>
      <a href="#" target="_blank">linkedi<span>n</span></a>
    </div>
  </header>
</template>

<script>
export default {
  name: "VKHeader",
};
</script>

<style lang="scss">
header {
  width: 100vw;
  padding: 3rem;
  margin-bottom: 4rem;
  background-color: rgba(65, 80, 47, 0.8);
  // box-shadow: 0px 1px 2rem 2rem rgba(65, 80, 47, 0.8);

  h1 {
    background: -webkit-linear-gradient(0deg, #ef886f 0%, #bed075 80%);
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;

    font-family: "Nothing You Could Do", Helvetica, sans-serif;
    font-size: 2rem;
    font-weight: 400;
    letter-spacing: -0.6;
    margin: 0 auto 2.5rem;
  }

  @media only screen and (min-width: 600px) {
    padding: 6rem 6rem 4rem;
    margin-bottom: 8rem;

    h1 {
      font-size: 4rem;
      font-weight: 400;
    }
  }

  @media only screen and (min-width: 840px) {
    h1 {
      text-align: center;
      font-size: 6rem;
      margin-bottom: 5rem;
    }
  }
}
</style>
