<template>
<div class="section1List">
    <ul class="section1Inf">
        <!-- <SectionCop :v-for="li in list" v-bind:li="li" /> -->
        <li class="section1InfImg">
            <img class="section1Img" src="@/assets/photo-1.png" alt="foto">
        </li>
        <li class="section1Item1">
            <p class="sectionData">10/10/2020</p>
            <p class="sectionItemTaitle">Lifestyle</p>
        </li>
        <li>
            <h3 class="section1TitleText">Lorem ipsum dolor sit amet, consectetur adipiscing</h3>
        </li>
        <li>
            <h6 class="section1Text">ut aut reiciendis voluptatibus maiores alias consequatur.</h6>
        </li>
    </ul>
    <ul class="section1Inf">
        <!-- <SectionCop :v-for="li in list" v-bind:li="li" /> -->
        <li class="section1InfImg">
            <img class="section1Img" src="@/assets/photo-2.png" alt="foto">
        </li>
        <li class="section1Item1">
            <p class="sectionData">10/10/2020</p>
            <p class="sectionItemTaitle">Lifestyle</p>
        </li>
        <li>
            <h3 class="section1TitleText">Lorem ipsum dolor sit amet, consectetur adipiscing</h3>
        </li>
        <li>
            <h6 class="section1Text">ut aut reiciendis voluptatibus maiores alias consequatur.</h6>
        </li>
    </ul>
</div>
</template>
<script>
// import SectionCop from '@/components/section1/SectionCop.vue';

export default {
  props: ['list'],
  components: {
    // SectionCop,
  },
};
</script>
<style scoped>
.section1List{
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 650px;
}
.section1Inf{
       list-style: none;
       padding: 0;
       margin: 0;
}
.section1InfImg{
       object-fit: cover;
       margin: 0;
       padding: 0;
}
.section1Item1{
       display: flex;
       justify-content: space-between;
       align-items: center;
}
.sectionData{
       font-family: 'Kanit', sans-serif;
       font-style: normal;
       font-weight: 500;
       font-size: 12px;
       line-height: 18px;
       letter-spacing: 6px;
       color: #000000;
}
.sectionItemTaitle{
    font-family: 'Kanit', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 12px;
    line-height: 18px;
    text-align: right;
    text-decoration-line: underline;
    color: #000000;
    text-transform: uppercase;
}
.section1TitleText{
    font-family: 'Kanit', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 24px;
    line-height: 36px;
    color: #1F1F1D;
}
.section1Text{
    font-family: 'Kanit', sans-serif;
    font-style: normal;
    font-weight: 300;
    font-size: 18px;
    line-height: 27px;
    color: #1F1F1D;
}
</style>
