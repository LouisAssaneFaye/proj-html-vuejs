<template>
    <div class="keyFeatures">
        <h1>
            Key Features
        </h1>
        <p>
            Start working with <span>Landrick</span> that can provide everything you need to generate <br>
            awareness, drive traffic, connect.
        </p>
        <div class="cards">
            <img src="../../assets/land/hover-box.png" alt="">
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
 div.keyFeatures{
    display: flex;
    flex-direction: column;
    width: 80%;
    margin: 0 auto;
    padding-top: 230px;
    h1{
        margin-bottom: 2rem;
    }
    p{
        margin-bottom: 3rem;
        span{
            color: blue;
            font-weight: bold;
        }
    }
 }

    
</style>