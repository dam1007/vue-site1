<template> 
  <HeaderSection />
  <SliderSection />
  <ImageSection skill="section"/>
  <ImgtextSection />
  <CardSection />
</template>

<script>
  import HeaderSection from './components/HeaderSection.vue'
  import SliderSection from './components/SliderSection.vue'
  import ImageSection from './components/ImageSection.vue'
  import ImgtextSection from './components/ImgtextSection.vue'
  import CardSection from './components/CardSection.vue'

  export default {
    name: 'App',
    components: {
      HeaderSection,
      SliderSection,
      ImageSection,
      ImgtextSection,
      CardSection,
    }
  }

</script>
<style>
  @import "./App.css";
</style>
