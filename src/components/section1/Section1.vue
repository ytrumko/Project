<template>
    <div class="mainContainer">
        <div class="section1Title">
            <h3 class="sectionTitle">Featured</h3>
        </div>
        <Section1List v-bind:list="list"/>
    </div>
</template>
<script>
import Section1List from '@/components/section1/Section1List.vue';

export default {
  data() {
    return {
      list: [
        {
          path: '<img src="@/assets/photo-1.png" alt="foto">',
        },
        {
          path: '"@/assets/photo-2.png"',
        },
      ],
    };
  },
  components: {
    Section1List,
  },
};
</script>
<style scoped>
.mainContainer{
    min-width: 1140px;
    padding: 0 150px;
    margin: 0 auto;
}
.section1Title{
    display: flex;
    justify-content: left;
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
</style>
