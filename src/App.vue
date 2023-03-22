<script>
import MainHeader from './components/header/MainHeader.vue';
import Main from './components/main/Main.vue';
export default {
  components: {
    MainHeader,
    Main
  }
}
</script>

<template>
  <div id="container">
    <MainHeader></MainHeader>
    <div class="mainSection">
      <Main></Main>
      <Main></Main>
    </div>
  </div>
</template>

<style scoped>
div #container {
  height: 100%;
  background-color: rgb(248, 235, 235);
}

.mainSection {
  padding-top: 100px;
}
</style>
