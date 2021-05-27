<template>
  <div class="TodoEdit">
    <div class="TodoDetail">
      <div class="detailHeader">
        <p class="deleteText">Delte</p>
        <p class="CanselText">Cansel</p>
      </div>
      <div class="todoTitle">
        <h1 class="TitleCaption">Title</h1>
        <div class="line TitleLine"></div>
        <h1 class="TitleName">SampleTitle</h1>
      </div>
      <div class="todoMemo">
        <h2 class="MemoCaption">memo</h2>
        <div class="line MemoLine"></div>
        <h2 class="MemoContents">
          Samplememo. I like Shark. So I define that I will make Shark figure. I
          have to buy some material.
        </h2>
      </div>
    </div>
    <div class="saveButton">
      <h2 class="saveButtonText">Save the Change</h2>
    </div>
  </div>
</template>
<style scoped>
.TodoEdit {
  width: 366px;
  height: 543px;
  background-color: #fcdb63;
  border-radius: 20px;
  margin: 0 auto 0 auto;
  left: 0;
  right: 0;
  top: 80px;
  position: absolute;
  box-shadow: 2px 4px 6px rgba(50, 50, 50, 0.25);
}
.line {
  background-color: #323232;
  height: 3px;
  width: 84px;
  margin: 0 0 0 40px;
}
.TodoDetail {
  width: 320px;
  height: 351px;
  background-color: white;
  margin: 0 auto 0 auto;
  top: 53px;
  left: 0;
  right: 0;
  position: absolute;
}
.detailHeader {
  display: flex;
  justify-content: flex-end;
  margin: 15px;
}
p.deleteText {
  color: #d95959;
  margin: 0 15px 0 0;
}
h1.TitleCaption {
  font-size: 30px;
  text-align: left;
  margin: -15px 0 0 40px;
}
h1.TitleName {
  font-size: 30px;
  margin: 15px 0 0 40px;
  text-align: left;
  max-width: 240px;
}
h2.MemoCaption {
  font-size: 25px;
  margin: 25px 0 0 40px;
  text-align: left;
}
h2.MemoContents {
  font-size: 22px;
  margin: 10px 0 0 40px;
  text-align: left;
  line-height: 26px;
  max-width: 240px;
}
.saveButton {
  position: absolute;
  margin: 0 auto 0 auto;
  top: 437px;
  left: 0;
  right: 0;
  width: 315px;
  height: 55px;
  background-color: #86dc8e;
  border-radius: 32px;
}
.saveButtonText {
  font-size: 20px;
  letter-spacing: 0.15em;
  padding: 16px 0 0 0;
}
</style>
<script>
export default {
  name: "TodoEdit",
};
</script>
