<template>
  <div class="GomibakoPlate">
    <div class="GomibakoSign">
      <div class="white">
        <h1 class="SignTitle">Gomibako</h1>
      </div>
    </div>
    <div class="Tasks">
      <div class="Task">
        <h2 class="Title">Title:SmapleText</h2>
        <p class="Caption">
          memo:This memo is Smaple. I want to fly very much. I like shark.
        </p>
      </div>
      <div class="Task">
        <h2 class="Title">Title:SmapleText</h2>
        <p class="Caption">
          memo:This memo is Smaple. I want to fly very much. I like shark.
        </p>
      </div>
      <div class="Task">
        <h2 class="Title">Title:SmapleText</h2>
        <p class="Caption">
          memo:This memo is Smaple. I want to fly very much. I like shark.
        </p>
      </div>
      <div class="Task">
        <h2 class="Title">Title:SmapleText</h2>
        <p class="Caption">
          memo:This memo is Smaple. I want to fly very much. I like shark.
        </p>
      </div>
    </div>
  </div>
</template>
<style scoped>
.GomibakoSign {
  position: absolute;
  top: -30px;
  left: 0;
  right: 0;
  margin: 0 auto 0 auto;
  background-color: #9d9c97;
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
.GomibakoPlate {
  width: 470px;
  min-height: 500px;
  background-color: #cdcbc3;
  border-radius: 20px;
  box-shadow: 2px 4px 6px rgba(0, 0, 0, 0.25);
}
.Tasks {
  margin: -30px 40px 0 64px;
  display: flex;
  flex-wrap: wrap;
}
.Task {
  background-color: white;
  width: 96px;
  height: 96px;
  justify-content: left;
  margin: 40px 24px 0 0;
}
h2.Title {
  font-size: 10px;
  text-align: left;
  margin-left: 7px;
  max-width: 84px;
  margin: 0 0 0 7px;
  padding-top: 12px;
}
p.Caption {
  max-width: 84px;
  font-size: 9px;
  font-weight: 700;
  margin: 0 0 0 7px;
  padding-top: 9px;
  text-align: left;
  line-height: 11px;
}
</style>
<script>
export default {
  name: "Gomibako",
};
</script>
