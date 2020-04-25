<template>
    <ul>
      <ArticleLi />
    </ul>
</template>
<script>
import ArticleLi from '@/components/article/ArticleLi.vue';

export default {
  data() {
    return {
      list: [
        { src: '../assets/Vector.png', taitle: 'Webdesign', text: 'Tincidunt lobortis feugiat vivamus at augue eget.' },
      ],
    };
  },
  components: {
    ArticleLi,
  },
};
</script>
<style scoped>
ul{
    list-style: none;
    display: flex;
    flex-direction: column;
}
</style>
