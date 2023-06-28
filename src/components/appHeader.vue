<template>
    <div class="appHeaderContainer">
        
        <div class="logo">
            <img src="../assets/land/img/logo-dark.png" alt="logo dark">
        </div>
        
        <div class="appHeader">
            <ul>
                <li>HOME</li>
                <li>LANDING</li>
                <li>PAGES</li>
                <li>DEMOS</li>
                <li>COMPONENTS</li>
                <li>DOCS</li>
            </ul>
        </div>

        <div class="icons">
            <i class="fa-solid fa-magnifying-glass"></i>
            <i class="fa-solid fa-gear"></i>


        </div>
        
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
@use '../styles/partials/variables';
@use '../styles/partials/mixins';
 
div.appHeaderContainer{
    z-index: 3;
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
    }
}
    
</style>