<template>
    <singleLinkOne v-for="linkOneObj in linkListOne" :linkElement ='linkOneObj' />
</template>
<script>
import singleLinkOne from './singleLinkOne.vue';
export default {
   components:{
    singleLinkOne
   },
   data(){
    return{
        linkListOne:[
            'About us',
            'Services',
            'Team',
            'Pricing',
            'Project',
            'Careers',
            'Blog',
            '',
        ]
    }
   }
    
}
</script>
<style lang="scss" scoped>
    
</style>