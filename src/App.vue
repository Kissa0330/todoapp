<template>
  <Header />
  <TopPage />
  <CreateButton />
  <TodoEdit/>
</template>

<script>
import TopPage from "./components/TopPage.vue";
import Header from "./components/Header";
import CreateButton from "./components/CreateButton"
import TodoEdit from "./components/TodoEdit"

export default {
  name: "App",
  components: {
    TopPage,
    Header,
    CreateButton,
    TodoEdit
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
  font-family: "Roboto", sans-serif;
  background-color: #fff7e3;
  color: #323232;
}
h1 {
  margin: 0;
}
p{
  font-size: 15px;
}
</style>
