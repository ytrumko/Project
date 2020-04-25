<template>
<li class="section1InfImg">
  {{li.path}}
    <!-- <img src="@/assets/photo-1.png" alt="foto"> -->
</li>
</template>
<script>
export default {
  props: ['li'],
};
</script>
<style scoped>
.section1InfImg{
       object-fit: cover;
       margin: 0;
       padding: 0;
}
</style>
