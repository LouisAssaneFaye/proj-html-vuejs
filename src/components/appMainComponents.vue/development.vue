<template>
    <div class="developmentContainer">
        <div class="left">
            <span class="firstSpan">
                Development
            </span>
            <h1>
                A Complete <br>
                Developer Toolset
            </h1>
            <p>
                Launch your compaign and benefit from our expertise on designing<br>
                and managing conversion centered bootstrap v5 html page.
            </p>
            <div class="buttons">
                <button class="blueButton">
                    Get Started
                </button>
                <button class="whiteButton">
                    Documentation
                </button>
            </div>
            <span class="secondSpan">
                Current Version: v4.7.0
            </span>
        </div>
        <div class="right">
            <img src="../../assets/land/img/about.png" alt="">
        </div>
    </div>
    <div class="under">
            <div class="amazon">
                <img src="../../assets/land/img/amazon.svg" alt="">
            </div>
            <div class="google">
                <img src="../../assets/land/img/google.svg" alt="">
            </div>
            <div class="lenovo">
                <img src="../../assets/land/img/lenovo.svg" alt="">
            </div>
            <div class="paypal">
                <img src="../../assets/land/img/paypal.svg" alt="">
            </div>
            <div class="shopify">
                <img src="../../assets/land/img/shopify.svg" alt="">
            </div>
            <div class="spotify">
                <img src="../../assets/land/img/spotify.svg" alt="">
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
    div.developmentContainer{
        padding-top: 80px;
        display: flex;
        width: 80%;
        margin: 0 auto;
        div.left{
            display: flex;
            flex-direction: column;
            margin-right: 95px;
            padding-top: 6rem;
            span.firstSpan{
                text-align: center;
                background-color: rgba(0, 179, 255, 0.3);
                color: blue;
                border-radius: 30px;
                width:7.5rem;
                margin-bottom: 2rem;
            }
            h1{
                margin-bottom: 2rem;
            }
            p{
                margin-bottom: 2rem;
                color: grey;
            }
            div.buttons{
                display: flex;
                margin-bottom: 1.6rem;
                button.blueButton{
                    font-weight: bold;
                    background-color: blue;
                    border-radius: 5px;
                    color: white;
                    margin-right: 10px;
                    height: 1.9rem;
                    width: 6.5rem;
                    border: 1px solid blue;
                }
                button.blueButton:hover{
                    background-color: rgb(0, 0, 184);
                }
                button.whiteButton{
                    font-weight: bold;
                    border: 1px solid blue;
                    color: blue;
                    border-radius: 5px;
                    height: 1.9rem;
                    width:7.5rem
                }
                button.whiteButton:hover{
                    background-color: blue;
                    color: white;
                    
                }
            }
            span.secondSpan{
                    color: grey;
            }
            
            

        }
    }
    div.under{
        display: flex;
        justify-content: space-between;
        padding-top: 220px;
        width: 75%;
        height: 50px;
        margin: 0 auto;
        img{
            width: 5rem;
        }
    }
    
</style>