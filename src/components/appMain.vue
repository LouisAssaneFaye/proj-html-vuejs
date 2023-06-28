<template>
    <div class="appMain">
        <div>
          <development />
       </div>
       <div>
          <keyFeauters />
       </div>
       <div>
          <quickStart />
       </div>
       <div>
          <buildTools />
       </div>
       <div>
           <ourRates />
       </div>
       <div>
           <wantToBe />
       </div>
       <div class="button">
           <i class="fa-solid fa-arrow-up"></i>
       </div>
       <div class="gear">
          <i class="fa-solid fa-gear"></i>
       </div>

    </div>
</template>
<script>
import wantToBe from './appMainComponents.vue/wantToBe.vue';
import ourRates from './appMainComponents.vue/ourRates.vue';
import buildTools from './appMainComponents.vue/buildTools.vue';
import quickStart from './appMainComponents.vue/quickStart.vue';
import keyFeauters from './appMainComponents.vue/keyFeauters.vue';
import development from './appMainComponents.vue/development.vue';
export default {
    name: 'appMain',
    components: {
        development,
        keyFeauters,
        quickStart,
        buildTools,
        ourRates,
        wantToBe,

    }
}
</script>
<style lang="scss" scoped>
@use '../styles/partials/variables';
@use '../styles/partials/mixins';

div.appMain{
    position: relative;
    div.button{
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: blue;
        border-radius: 5px;
        color: white;
        height: 3rem;
        width: 3rem;
        position: fixed;
        top: 650px;
        right: 30px;
       }
    div.gear{

        display: inline-block;
        text-align: center;
        line-height: 3rem;
        height: 3rem;
        width: 3rem;
        color: blue;
        background-color: white;
        font-size: 1.5rem;
        border-radius: 50%;
        position: fixed;
        top:245px;
        left:10px 
    }
   
 }
    
</style>