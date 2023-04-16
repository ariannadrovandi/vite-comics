<template>
  <div>
    <HeaderComponent />
    <MainComponent />
    <MainBottomComponent />
    <FooterComponent />
    <FooterBottomComponent />
  </div>
</template>

<script>
  import HeaderComponent from './components/HeaderComponent.vue';
  import MainComponent from './components/MainComponent.vue';
  import MainBottomComponent from './components/MainBottomComponent.vue';
  import FooterComponent from './components/FooterComponent.vue';
  import FooterBottomComponent from './components/FooterBottomComponent.vue';
  export default {
    name: 'App',
    components: {
      HeaderComponent,
      MainComponent,
      MainBottomComponent,
      FooterComponent,
      FooterBottomComponent,
    }
  };
</script>

<style lang="scss" scoped>
  
</style>

