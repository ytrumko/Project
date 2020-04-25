<template>
<div class="baner">
  <div class="banerImg">
    <img class="banerImgFoto" src="@/assets/philip-martin.jpg" alt="foto">
  </div>
  <BanerList />
</div>
</template>
<script>
import BanerList from '@/components/header/BanerList.vue';

export default {
  components: {
    BanerList,
  },
};
</script>
<style scoped>
.banerImg{
    object-fit: cover;
    height: 100%;
}
.baner{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 570px;
}
</style>
