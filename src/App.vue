<script>
import appHeader from './components/appHeader.vue';
import appMain from './components/appMain.vue';
import appFooter from './components/appFooter.vue';
export default {
  name: 'App',
  components:{
    appHeader,
    appMain,
    appFooter
  }
}
</script>

<template>
  <div class="appHeader">
    <appHeader />
  </div>
  <appMain />
  <appFooter />
</template>

<style lang="scss" >
@import './styles/general.scss';
div.appHeaderContainer{
 position: fixed;
 z-index: 1;
 background-color: white;
}

</style>
