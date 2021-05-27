<template>
  <div class="CreateButton">
    <div class="createButtonContainer">
      <h2 class="ButtonText">Create new ToDo</h2> <img src="../assets/check.svg" alt="check">
    </div>
  </div>
</template>
<style scoped>
.CreateButton {
  position: fixed;
  top: 620px;
  right: 10px;
  left: auto;
  z-index: 500;
  background-color: #86dc8e;
  width: 315px;
  height: 55px;
  border-radius: 32px;
  box-shadow: 2px 4px 6px rgba(50, 50, 50, 0.25);
}
.createButtonContainer {
  padding-top: 16px;
  display: flex;
  justify-content: center;
}
h2.ButtonText {
  font-size: 20px;
  letter-spacing: 0.15em;
  margin: 0 15px 0 0;
}
</style>
<script>
export default {
  name: "CreateButton",
};
</script>
