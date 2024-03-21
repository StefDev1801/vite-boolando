<script>
import AppHeader from './components/AppHeader.vue';//importo il componente
import AppMain from './components/AppMain.vue';//importo il componente
import AppFooter from './components/AppFooter.vue';//importo il componente


export default{
  name: 'App',
  components: {
    AppHeader: AppHeader,//registro il componente
    AppMain: AppMain,
    AppFooter: AppFooter
  }
}
</script>

<template>

  <AppHeader/>
  <AppMain/>
  <AppFooter/>

</template>

<style></style>
