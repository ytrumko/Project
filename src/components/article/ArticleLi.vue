<template>
<div>
   <li class="ico">
        <img class="imgIco" alt="1" src="@/assets/Vector.png">
        <h1 class="taitle">list.taitle</h1>
        <p class="text">Tincidunt lobortis feugiat vivamus at augue eget.</p>
    </li>
</div>
</template>
<script>
export default {
  props: ['list'],
};
</script>
<style scoped>
div{
    display: flex;
}
.ico{
/* position: absolute; */
width: 72px;
height: 72px;
background: rgba(196, 196, 196, 0.02);
border: 1px solid rgba(255, 255, 255, 0.1);
box-sizing: border-box;
/* margin-bottom: 18px; */
}
.imgIco{
/* position: absolute; */
width: 25.58px;
height: 20.46px;
/* Colors/Tetriary */
/* background: #00F0B5;
border: 1px solid #CF4646;
box-sizing: border-box; */
}
.taitle{
/* position: absolute; */
width: 89px;
height: 27px;
font-family: Kanit;
font-style: normal;
font-weight: 500;
font-size: 18px;
line-height: 27px;
color: #000000;
}
.text{
/* position: absolute; */
width: 318px;
height: 80px;
font-family: Kanit;
font-style: normal;
font-weight: normal;
font-size: 16.2px;
line-height: 163.35%;
color: #000000;
}
</style>
