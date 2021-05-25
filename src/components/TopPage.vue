<template>
  <div class="Container">
    <Kanban />
    <Gomibako />
  </div>
</template>

<script>
import Kanban from "./Kanban";
import Gomibako from "./Gomibako";
export default {
  name: "toppage",
  components: {
    Kanban,
    Gomibako,
  },
};
</script>

<style>
.Container {
  margin: 80px 0 0 0;
  display: flex;
  justify-content: center;
}
</style>
