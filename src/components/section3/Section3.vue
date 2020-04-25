<template>
    <div class="mainContainer">
       <div class="sectionWrap">
           <div class="section3Img">
                <img src="@/assets/photo-3.png" alt="foto">
            </div>
            <Section3List />
       </div>
    </div>
</template>
<script>
import Section3List from '@/components/section3/Section3List.vue';

export default {
  components: {
    Section3List,
  },
};
</script>
<style scoped>
.mainContainer{
    min-width: 1140px;
    padding: 0 150px;
    margin: 0 auto;
}
.sectionWrap{
    display: flex;
    justify-content: center;
    align-items: center;
}
.section3Img{
    object-fit: cover;
}
