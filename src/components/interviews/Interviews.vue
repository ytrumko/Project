<template>
    <div class="mainContainer">
       <h3 class="sectionTitle">INTERVIEWS</h3>
       <SectionInf />
       <div class="sectionButton">
            <button class="sectionButtonText">See all</button>
        </div>
    </div>
</template>
<script>
import SectionInf from '@/components/interviews/SectionInf.vue';

export default {
  components: {
    SectionInf,
  },
};
</script>
<style scoped>
.mainContainer{
    min-width: 1140px;
    padding: 0 150px;
    margin: 0 auto;
}
.sectionTitle{
    font-family: 'Kanit', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 18px;
    line-height: 27px;
    color: #1F1F1D;
    text-transform: uppercase;
    padding-top: 60px;
    padding-bottom: 30px;
}
.sectionButton{
    display: flex;
    justify-content: center;
    align-items: center;
   }
.sectionButtonText{
    font-family: 'Kanit', sans-serif;
    background: #303030;
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 21px;
    text-align: center;
    color: #FFFFFF;
    text-transform: uppercase;
    padding-top: 11px;
    padding-bottom: 10px;
    padding-right: 87px;
    padding-left: 88px;
    border: none;
}
