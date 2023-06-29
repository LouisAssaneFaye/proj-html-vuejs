<template>
    <div class="appHeaderContainer">
        
        <div class="logo">
            <img src="../assets/land/img/logo-dark.png" alt="logo dark">
        </div>
        
        <div class="appHeader">
            <ul>
                <links />
            </ul>
        </div>

        <div class="icons">
            <i class="fa-solid fa-magnifying-glass"></i>
            <i class="fa-solid fa-gear"></i>
        </div>
        
        
    </div>
</template>
<script>
import links from './appHeaderComponents.vue/links.vue';
export default {
    name:'appHeader',
    data(){
        return{

        }
    },
    components:{
        links
    }
    
}
</script>
<style lang="scss" scoped>
@use '../styles/partials/variables';
@use '../styles/partials/mixins';
 
div.appHeaderContainer{
    position: fixed;
    right: 10%;
    display: flex;
    justify-content: space-between;
    width:80%;
    height: 60px;
    margin: 0 auto;
    div.logo{
        display: flex;
        align-items: center;
        img{
            width: 8rem;
            
        }
    }
    div.appHeader{
        margin-left: 8.5rem;
        width: 55%;
        font-weight: bold;
       ul{
           display: flex;
           list-style: none;
           justify-content: space-between;
           font-size: 0.8rem;
           height: 100%;
           align-items: center;
           div.landingHover{
             display: none;
             width: 100%;
             background-color: white;
             z-index: 2;
             position: absolute;
             top:4rem;
             left: 0rem;
             border: 1px solid black;
             justify-content: space-between;
             font-weight: bold;
             div{
                ul{
                  list-style-type: none;
                  display: flex;
                  flex-direction: column;
                  align-items: flex-start;
                    li{
                        margin-bottom: 20px;
                    }   
                }
            }
          }

            li.landing:hover ~ div.landigHover{
            display: flex;
           }

       }
}

    div.icons{
       display: flex;
       justify-content: flex-end;
       align-items: center;
       width: 20%;
       i{
        margin-right: 20px;
       }
       i.fa-gear{
        background-color: rgb(192, 230, 255);
        padding: 1rem;
        border-radius: 5px;
       }
       i.fa-gear:hover{
        background-color: blue;
       }
    }

    
}
    
</style>