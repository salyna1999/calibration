<template>
  <v-app dark>
    <v-container>
      <v-btn class="b">Text</v-btn>
      <v-btn class="b1">Message</v-btn>
    </v-container>
  </v-app>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.b {
  background-color: #581845;
  border: none;
  color: white;
  text-align: center;
  padding: 16px 32px;
  font-size: 20px;
  margin: 50px 2px;
  transition-duration: 0.4s;
  width: 80%;
}
.b:hover {
  background-color: #900c3f;
  color: black;
}
.b1 {
  background-color: #581845;
  border: none;
  color: white;
  text-align: center;
  padding: 50px 50px;
  font-size: 20px;
  margin: 50px 2px;
  transition-duration: 0.4s;
  width: 80%;
}
.b1:hover {
  background-color: #900c3f;
  color: black;
}
</style>
