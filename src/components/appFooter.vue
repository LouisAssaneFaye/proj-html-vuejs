<template>
    <div class="appFooter">
        <div class="up">
            <div class="landrick">
                
                <img src="../assets/land/img/logo-light.png" alt="">
                
                <p>
                    Start working with Landrick can provide <br>
                    everything you need to generate awareness, <br>
                    drive traffic, connect.
                </p>

                <ul>
                    <li><i class="fa-sharp fa-regular fa-cart-shopping"></i></li>
                    <li><i class="fa-sharp fa-light fa-globe"></i></li>
                    <li><i class="fa-brands fa-behance"></i></li>
                    <li><i class="fa-brands fa-facebook"></i></li>
                    <li><i class="fa-brands fa-instagram"></i></li>
                    <li><i class="fa-brands fa-twitter"></i></li>
                    <li><i class="fa-regular fa-envelope"></i></li>
                </ul>
                
            </div>
            <div class="company">
                <h3>
                    Company
                </h3>
                <ul>
                    <linksOne />
                </ul>
            </div>
            <div class="usefull">
                <h3>
                    Usefull Liks
                </h3>
                <ul>
                    <linksTwo />
                </ul>
            </div>
            <div class="newsletter">
                <h3>
                    Newsletter
                </h3>
                <p>
                    Sign up and receive the latest tips <br>
                    via email.
                </p>
                <div class="input">
                    <div>
                        Write your email
                    </div>
                    <input type="text" placeholder="              Your email:">
                    <div class="button">
                        <button>Subscribe</button>
                    </div>
                </div>
            </div>
        </div>
        <div class="down">
            <div class="left">
                <i class="fa-solid fa-c"></i> 2023 Lnadrick. Design with <i class="fa-solid fa-heart"></i> by Shreethems.
            </div>
            <div class="right">
                <img src="../assets/land/img/american-ex.png" alt="">
                <img src="../assets/land/img/discover.png" alt="">
                <img src="../assets/land/img/master-card.png" alt="">
                <img src="../assets/land/img/paypal.png" alt="">
                <img src="../assets/land/img/visa.png" alt="">
            </div>

        </div>
    </div>
</template>
<script>
import linksOne from './appFooterComponents.vue/linksOne.vue';
import linksTwo from './appFooterComponents.vue/linksTwo.vue';
export default {
    name:'appFooter',
    data(){
        return{

        }
    },
    components:{
        linksOne,
        linksTwo
        
    }
    
}
</script>
<style lang="scss" scoped>
@use '../styles/partials/variables';
@use '../styles/partials/mixins';
div.appFooter{
    color: #adb5bd;
    background-color: rgb(32, 41, 66);
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 3.5em;
    margin-top: 5rem;
    div.up{
        width: 80%;
        display: flex;
        justify-content: space-between;
        margin-bottom: 5rem;
        div.landrick{
            img{
                width: 7rem;
                margin-bottom: 1.5rem;
            }
            p{
                margin-bottom: 1.5rem;
            }
            ul{
                display: flex;
                list-style-type: none;
                li{
                    margin-right: 23px;
                    i{
                        height: 2rem;
                        width: 2rem;
                        padding-left: 0.5rem;
                        line-height: 2rem;
                        border-radius: 10px;
                    }
                }
                li:hover{
                    background-color: blue;
                    i{
                        height: 2rem;
                        width: 2rem;
                        line-height: 2rem;
                    }
                }
            }
        }
        div.company{
            h3{
                margin-bottom: 1.5rem;
                color: white;
            }
            ul{
                list-style-type: none;
            }
        }
        div.usefull{
            h3{
                margin-bottom: 1.5rem;
                color: white;
            }
            ul{
                list-style-type: none;
            }
        }
        div.newsletter{
            display: flex;
            flex-direction: column;
            h3{
                margin-bottom: 1.5rem;
                color: white;
            }
            p{
                margin-bottom: 1.5rem;
            }
            div{
                margin-bottom: 15px;
            }
            input{
                margin-bottom: 15px;
                width: 15rem;
                height: 2.5rem;
                border-radius: 5px;
                border: 0;
                
            }
            div.button{
                button{
                    width: 15rem;
                    height: 2.5rem;
                    border-radius: 5px;
                    border: 0;
                    color: blue;
                    font-weight: bold;
                    
                }
                button:hover{
                    color: white;
                    background-color: blue
                    
                }
            }
        }

    }
    div.down{
        width: 80%;
        display: flex;
        justify-content: space-between;
        align-self: center;
        padding-bottom: 2rem;
        div.right{
            img{
                margin-right: 5px;
                width: 2rem;
            }
        }
        div.left{
            i.fa-heart{
                color: red;
            }
        }
    }
}
    
</style>