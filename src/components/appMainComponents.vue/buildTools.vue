<template>
    <div class="buildTools">
        <div class="left">
            
            <h1>
                Build tools and exstensive documentation
            </h1>
            <p>
                You can combine all the Landrick templates into a single one, you can take a <br>
                component from the Application theme and use it in the Website.
            </p>
            <ul>
                <li>Digital Marketing Solutions for Tomorrow</li>
                <li>Our Talented & Experenced Marketing Agency</li>
                <li>Create your own skin to match your brand</li>
            </ul>
            <img src="../../assets/land/hover-button.png" alt="">

        </div>

        <div class="right">
            <img src="../../assets/land/img/1.png" alt="">
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
 @use '../../styles/partials/variables';
 @use '../../styles/partials/mixins';
div.buildTools{
    width: 80%;
    display: flex;
    margin-top: 10rem;
    margin: 0 auto;
    div.left{
        display: flex;
        flex-direction: column;
        padding-top: 12rem;
        h1{
            margin-bottom: 2rem;
        }
        p{
            margin-bottom: 1.5rem;
        }
        ul{
            margin-bottom: 1.5rem;
            list-style-type: none;
            li{
                margin-bottom: 0.5rem;
            }
        }
        img{
            width: 15rem;
            margin-left: -2.2rem;
        }
    }
    div.right{
        padding-top: 8rem;
        width: 40;
        margin-left: 4rem;
        img{
            width: 100%;
            height: 30rem;
        }
    }
    
}
    
</style>