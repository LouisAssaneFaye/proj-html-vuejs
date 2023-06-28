<template>
    <div class="quickStart">
        
        <span class="blue">
            Quickstart
        </span>
        <h1>
            Awesome isn't it? Let's dive in!
        </h1>
        <p>
            Start working with <span class="blue">Landrick</span> that can provide everything you need to generate <br>
            awareness, drive traffic, connect.
        </p>
        <div class="tableContainer">
            <div class="table">
                <div class="npm">
                    npm
                </div>
                <div class="nuget">
                    nuget
                </div>
                <div class="spm">
                    spm
                </div>
                <div class="gitHub">
                    gitHub
                </div>
            </div>
            <div class="install">
                <span class="green">
                    $
                </span>
                <span>
                    npm install -
                </span>
                <span class="green">
                    g
                </span>
                <span>
                    claps.js
                </span>
            </div>
        </div>
        <div class="underTable">
            <div>
                <span class="green">
                    <i class="fa-regular fa-circle-chevron-down"></i>
                </span>
                Organize your data
            </div>
            <div>
                <span class="green">
                    <i class="fa-regular fa-circle-chevron-down"></i>
                </span>
                Work with any team
            </div>
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
div.quickStart{
    width: 55%;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    display: flex;
    align-items: center;
    span.blue{
        color: blue;
        margin-bottom: 1rem;
    }
    h1{
        margin-bottom: 2rem;
    }
    p{
        text-align: center;
        color: gray;
        margin-bottom: 1rem;
        span.blue{
            color: blue;
        }
    }
    div.tableContainer{
        background-color: black;
        border-radius: 5px;
        color: grey;
        width: 100%;
        padding-top: 1.2rem;
        margin-bottom: 2rem;
        
       div.table{
        width: 90%;
        display: flex;
        margin: 0 auto;
        justify-content: center;
        border-radius: 5px;
        background-color: rgba(167, 165, 165, 0.278);
        margin-bottom: 1rem;
        *{
            width: 25%;
            height: 2rem;
            text-align: center;
            line-height: 2rem;
            
        }
       }
       div.install{
            width: 90%;
            margin: 0 auto;
            margin-bottom: 2rem;
            span.green{
                color: rgb(103, 205, 103);
            }
        }
    }
    div.underTable{
            width: 50%;
            margin-right: 25rem;
            display: flex;
            justify-content: space-between;
            color: grey;
            i{
                color: rgb(103, 205, 103);
            }

    }
    
}
    
</style>