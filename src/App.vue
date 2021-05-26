<template>
  <Header />
  <TopPage />
</template>

<script>
import TopPage from "./components/TopPage.vue";
import Header from "./components/Header";

export default {
  name: "App",
  components: {
    TopPage,
    Header,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700&display=swap");
@import url("./static/reset.css");
body {
  text-align: center;
  margin: 0 auto 0 auto;
  height: auto;
  background: #fff7e3;
  font-family: "Roboto", sans-serif;
  color: #323232;
}
h1 {
  margin: 0;
}
</style>
