<template>
  <div id="myProgress">
    <div id="myBar">
      <v-container class="vl"></v-container>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
#myProgress {
  width: 100%;
  background-color:#898989;
  height: 60px;
}

#myBar {
  width: 50%;
  height: 60px;
  background-color: #00E5B1;
}

.vl {
  margin-top: 255px;
  border-left: 6px solid#000000;
  height: 80px;
  position: absolute;
  left: 40%;
  margin-left: -3px;
  top: 0;
}
</style>
