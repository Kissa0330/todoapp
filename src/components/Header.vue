<template>
  <header>
    <div class="HeaderBox">
      <h1 class="HeaderText">Todo App</h1>
    </div>
  </header>
</template>
<style scoped>
header {
  background-color: #6ca7ff;
  height: 74px;
  box-shadow: 0 4px 4px  rgba(0,0,0,0.25);
}
.HeaderBox {
  position: absolute;
  width: 286px;
  height: 41px;
  background-color: white;
  margin: 0 auto 0 auto;
  left: 0;
  right: 0;
  top: 16px;
  border-radius: 32px;
}
.HeaderText {
  font-size: 25px;
  letter-spacing: 0.15em;
  padding: 6px 0 6px 0;
}
</style>
<script>
export default {
  name: "Header",
};
</script>
