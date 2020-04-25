<template>
    <div class="mainContainer">
       <Section2List />
       <div class="sectionButton">
            <button class="sectionButtonText">See all</button>
        </div>
    </div>
</template>
<script>
import Section2List from '@/components/section2/Section2List.vue';

export default {
  components: {
    Section2List,
  },
};
</script>
<style scoped>
.mainContainer{
    min-width: 1140px;
    padding: 0 150px;
    margin: 0 auto;
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
</style>
