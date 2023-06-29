<template>
    <singleLink v-for="linkObj in linkList" :linkElement="linkObj" />
</template>
<script>
import singleLink from './singleLink.vue';
export default {
    name:'links',
    components:{
        singleLink
    },
    data(){
        return{
            linkList:[
                'HOME',
                'LANDING',
                'PAGES',
                'DEMOS',
                'COMPONENTS',
                'DOCS'
            ]
        }
    }
    
}
</script>
<style lang="scss" scoped>
    
</style>