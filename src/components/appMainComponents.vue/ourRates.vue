<template>
    <div class="ourRates">
        <div class="up">
            <h1>
                Our rates for developer from landrick team
            </h1>
            <p>
                Start working with <span class="blue">Landrick</span> that can provide everything you need to generate <br>
                awareness, drive traffic, connect.
            </p>
        </div>
        <div class="down">
            <img src="../../assets/land/hover-prices.png" alt="">
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
    div.ourRates{
    width: 80%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin: 0 auto;
        div.up{
            display: flex;
            flex-direction: column;
            h1{
                margin-bottom: 2rem;
                margin-top: 6rem;
            }
            p{
                text-align: center;
                color: grey;
                span.blue{
                    color: blue;
                }
                
            }
        }
        div.down{
            padding-top: 3rem;
            width: 100%;
            img{
                width: 100%;
                height: 34rem;
            }
        }

    }
</style>