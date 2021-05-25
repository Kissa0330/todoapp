<template>
  <div class="KanbanPlate">
    <div class="KanbanSign">
      <div class="white">
        <h1 class="SignTitle">Kanban</h1>
      </div>
    </div>
  </div>
</template>
<style scoped>
.KanbanSign {
  position: absolute;
  top: -30px;
  left: 0;
  right: 0;
  margin: 0 auto 0 auto;
  background-color: #d6bb57;
  width: 269px;
  height: 50px;
  position: relative;
  border-radius: 4px;
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
  border-radius: 4px;
}
.SignTitle {
  font-size: 20px;
  letter-spacing: 0.3em;
  padding: 4px 0 0 0;
}
.KanbanPlate {
  width: 470px;
  min-height: 500px;
  background-color: #fcdb63;
  border-radius: 20px;
  margin: 0 70px 0 0;
  box-shadow: 2px 4px 6px rgba(0, 0, 0, 0.25);
}
</style>
<script>
export default {
  name: "Kanban",
};
</script>
