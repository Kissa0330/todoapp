<template>
  <div class="KanbanSign">
    <div class="white">
      <h1 class="SignTitle">Kanban</h1>
    </div>
  </div>
  <div class="KanbanPlate"></div>
</template>
<style scoped>
.KanbanSign {
  background-color: #d8c171;
  width: 269px;
  height: 50px;
  position: relative;
}
.white {
  position: absolute;
  top: 9.5px;
  margin: 0 auto 0 auto;
  left: 0;
  right: 0;
  background-color: white;
  width: 216px;
  height: 31px;
}
.SignTitle {
  font-size: 20px;
  letter-spacing: 0.3em;
  padding: 4px 0 0 0;
}
</style>
<script>
export default {
  name: "Kanban",
};
</script>
