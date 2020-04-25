<template>
<div class="headerContainer">
  <div class="header">
    <button class="header__button"><img alt="bg" src="../assets/burger.svg"></button>
    <img alt="logo" src="../assets/Group 13.svg">
  </div>
  <About />
</div>
</template>
<script>
import About from '@/views/About.vue';

export default {
  name: 'Home',
  components: {
    About,
  },
};
</script>
<style scoped>
.headerContainer{
  display: flex;
  flex-direction: column;
  min-width: 1440;
  margin: 0 auto;
}
.header {
display: flex;
justify-content: center;
position: relative;
align-items: center;
padding: 46px 0px;
}
.header__button {
width: 40px;
height: 30px;
border: none;
box-shadow: none;
position: absolute;
left: 50px;
display: flex;
flex-direction: column;
justify-content: space-between;
align-items: stretch;
padding: 4px 2px;
background: none;
}
</style>
