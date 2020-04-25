<template>
    <div class="mainContainer">
        <div class="footerWrap">
            <img class="footerImg" src="@/assets/Group 2.png" alt="">
            <h6 class="footerText">Designed by Suffix </h6>
        </div>
    </div>
</template>
<style scoped>
.mainContainer{
    min-width: 1140px;
    padding: 0 150px;
    margin: 0 auto;
}
.footerWrap{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background: #000000;
    padding-top: 55px;
}
.footerText{
    font-family: 'Kanit', sans-serif;
    font-style: normal;
    font-weight: 300;
    font-size: 12px;
    line-height: 18px;
    text-align: center;
    color: #FFFFFF;
}
.footerImg{
    padding-bottom: 40px;
}
</style>
