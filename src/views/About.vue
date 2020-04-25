<template>
  <div class="about">
    <HeaderBaner />
    <Article />
    <Section1 />
    <Section2 />
    <Section3 />
    <Interviews />
    <News />
    <Footer />
  </div>
</template>
<script>
import HeaderBaner from '@/components/header/HeaderBaner.vue';
import Article from '@/components/article/Article.vue';
import Section1 from '@/components/section1/Section1.vue';
import Section2 from '@/components/section2/Section2.vue';
import Section3 from '@/components/section3/Section3.vue';
import Interviews from '@/components/interviews/Interviews.vue';
import News from '@/components/news/News.vue';
import Footer from '@/components/footer/Footer.vue';

export default {
  components: {
    HeaderBaner,
    Article,
    Section1,
    Section2,
    Section3,
    Interviews,
    News,
    Footer,
  },
};
</script>
