<template>
    <div class="appHeaderContainer">
        
        <div class="logo">
            <img src="../assets/land/img/logo-dark.png" alt="logo dark">
        </div>
        
        <div class="appHeader">
            <ul>
                <li class="home">HOME</li>
                <li class="landing">LANDING</li>
                <li class="pages">PAGES</li>
                <li class="demos">DEMOS</li>
                <li class="components">COMPONENTS</li>
                <li class="docs">DOCS</li>
                <div class="landingHover">
                   <div>
                       <ul>
                          <li class="title">LANDING PAGES</li>
                          <li>SAAS</li>
                          <li>CLASSIC SAAS</li>
                          <li>MODERN SAAS</li>
                          <li>AGENCY</li>
                          <li>APPLICATION</li>
                          <li>CLASSIC APP</li>
                          <li>MODERN APP</li>
                          <li>STUDIO</li>
                          <li>MARKETING</li>
                          <li>ENTERPRISE</li>
                          <li>SERVICE</li>
                          <li>PAYMENTS</li>
                          <li>IT SOLUTION</li>
                          <li>IT SOLUTIONS TWO</li>
                        </ul>
                    </div>
                    <div>
                        <ul>
                          <li class="title">LANDING PAGES</li>
                          <li>DEVELOPER</li>
                          <li>SEO AGENCY</li>
                          <li>HOSPITAL</li>
                         <li>COWORKING</li>
                         <li>BUSINESS</li>
                         <li>MODERN BUSINESS</li>
            <li>FINANCE</li>
            <li>DELIVERY AND LOGISTICS</li>
            <li>SOCIAL MEDIA</li>
            <li>DIGITAL AGENCY</li>
            <li>CUSTOMER</li>
            <li>SOFTWARE</li>
            <li>YOGA</li>
            <li>GYM & FITNESS</li>
            </ul>
        </div>
        <div>
            <ul>
                <li class="title">LANDING PAGES</li>
            <li>HOTEL</li>
            <li>RESTURANT</li>
            <li>CONSTRUCTIONL</li>
            <li>VIDEO CONFERENCE</li>
            <li>BLOCKCHAIN</li>
            <li>CRYPTOCURRENCY TWO</li>
            <li>INTEGRATION</li>
            <li>TASK MANAGEMENT</li>
            <li>EMAIL INBOX</li>
            <li>TRAVEL</li>
            <li>COURSE</li>
            <li>ONLINE LEARNING</li>
            <li>INSURANCE</li>
            <li>FURNITURE</li>
            </ul>
        </div>
        <div>
            <ul>
                <li class="title">LANDING PAGES</li>
            <li>LAW FIRM</li>
            <li>PRODUCT</li>
            <li>CAR RIDE</li>
            <li>LANDING ONE</li>
            <li>LANDING TWO</li>
            <li>LANDING THREE</li>
            <li>LANDING FOUR</li>
            <li>CHARITY</li>
            <li>PERSONAL</li>
            <li>CRATIVE PERSONAL</li>
            <li>FREELANCE</li>
            <li>EVENT</li>
            <li>E-BOOK</li>
            <li>SASS</li>
            </ul>
        </div>
        <div>
            <ul>
                <li class="title">FULL DEMOS</li>
            <li>CORPORATE</li>
            <li>CRYPTOCURRENCY</li>
            <li>SHOP</li>
            <li>PORTFOLIO</li>
            <li>HELP CENTER</li>
            <li>HOSTING & DOMAIN</li>
            <li>JOBS & CAREERS</li>
            <li>VIDEO STUDIO</li>
            <li>REAL ESTATE</li>
            <li>FORUMS</li>
            <li>BLOG OR NEWS</li>
            <li>NFT MARKETPLACE</li>
            <li>PHOTOGRAPHY</li>
            </ul>
        </div>
        </div>
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
   position: relative;
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