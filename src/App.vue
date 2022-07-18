<template> 
  <HeaderSection font="nexon" color="red" size="16px" />
  <SliderSection />
  <ImageSection skill="section" />
  <ImgtextSection />
  <CardSection />
  <BannerSection />
  <TextSection />
  <FooterSection />
</template>

<script>
  import HeaderSection from './components/HeaderSection.vue'
  import SliderSection from './components/SliderSection.vue'
  import ImageSection from './components/ImageSection.vue'
  import ImgtextSection from './components/ImgtextSection.vue'
  import CardSection from './components/CardSection.vue'
  import BannerSection from './components/BannerSection.vue'
  import TextSection from './components/TextSection.vue'
  import FooterSection from './components/FooterSection.vue'

  export default {
    name: 'App',
    components: {
      HeaderSection,
      SliderSection,
      ImageSection,
      ImgtextSection,
      CardSection,
      BannerSection,
      TextSection,
      FooterSection,
    }
  }

</script>
<style>
  @import "./App.css";
</style>
