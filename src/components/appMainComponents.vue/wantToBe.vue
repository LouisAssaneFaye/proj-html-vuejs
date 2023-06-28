<template>
    <div class="wantToBe">
        <h1>
            Want to be among the first to find out?
        </h1>
        <p>
            Start working with <span class="blue">Landrick</span> that can provide everything you need to generate <br>
            awareness, drive traffic, connect.
        </p>
        <div class="input">
            <input type="text" placeholder="     E-mail">
            <button class="bluButton">
                Get Started
            </button>
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
    div.wantToBe{
        padding-top: 5rem;
        width: 80%;
        margin: 0 auto;
        display: flex;
        flex-direction: column;
        align-items: center;
        h1{
            margin-bottom: 2rem;
        }
        p{
            color: grey;
            text-align: center;
            margin-bottom: 2rem;
            span.blue{
                color: blue;
            }
        }
        div.input{
            width: 100%;
            display: flex;
            justify-content: center;
            input{
                width:40%; 
                height: 2rem;
                border-radius: 20px;
                border: 1px solid lightgrey;
            }
            button{
                height: 2rem;
                border-radius: 20px;
                padding-left:1rem ;
                padding-right:1rem ;
                margin-left: -2rem;
                border: 0;
                background-color: blue;
                color: white;
                font-weight: bold;
            }
        }


    }
</style>