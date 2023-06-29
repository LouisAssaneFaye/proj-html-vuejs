<template>
    <singleLinkTwo v-for="linkTwoObj in linkListTwo" :linkElement="linkTwoObj" />
</template>
<script>
import singleLinkTwo from './singleLinkTwo.vue';
export default {
    components:{
        singleLinkTwo
    },
    data(){
        return{
            linkListTwo:[
                'Terms of Services',
                'Privacy Policy',
                'Documentation',
                'Changelog',
                'Components',
            ]
        }
    }

    
}
</script>
<style lang="scss" scoped>

    
</style>