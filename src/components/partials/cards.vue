<script>
export default {
    
}
</script>

<template>
    <div class="cards-container container">
        <h2 class="text-center">Trusted by Leading Organisations</h2>
        <div class="row">
            <div class="col-4 reveal fade-left">
                <img src="../../assets/img/case-studies-1-400x450.jpg" alt="">
                <div class="faded"></div>
                <div class="mt-3 mb-5">
                    <span class="info">
                        How Spaces attracted five million visitors by improving the content
                    </span>
                </div>
                <div>
                    <div class="number">200%</div>
                    <span>Higher revenue from digital</span>
                </div>
            </div>
            <div class="col-4 reveal">
                <img src="../../assets/img/case-studies-4-400x450.jpg" alt="">
                <div class="faded"></div>
                <div class="mt-3 mb-5">
                    <span class="info">
                        Creativity helped Hemisferio to increase their brand reach vertically
                    </span>
                </div>
                <div>
                    <div class="number">10x</div>
                    <span>Sales increase with the same ad spend</span>
                </div>
            </div>
            <div class="col-4 reveal fade-right">
                <img src="../../assets/img/case-studies-6-400x450.jpg" alt="">
                <div class="faded"></div>
                <div class="mt-3 mb-5">
                    <span class="info">
                        How DigitalBox used AI-powered data insight to boost sales
                    </span>
                </div>
                <div>
                    <div class="number">3-year</div>
                    <span>Partnership with Avada Consultant</span>
                </div>
            </div>
        </div>
        <div class="text-center">
            <button class="dc-button">Read More Cases Studies</button>
        </div>
    </div>
  
</template>

<style lang="scss">
@use '../../scss/partials/palette' as *;
 .cards-container{
    margin-top: 150px;
    h2{
        font-size: 60px;
        margin-bottom: 100px;
    }
    .row{
        .col-4{
            position: relative;
            img{
                &:hover{
                    cursor: pointer;
                }
            }
            .faded{
                position: absolute;
                width: 400px;
                bottom: 316px;
                height: 100%;
                opacity: 0;
                background: linear-gradient(180deg, transparent, rgba(37,37,37,0.01),$orange);
                transition: all 1.5s;
                &:hover{
                    cursor: pointer;
                    opacity: 1;
                }
                
            }
        }
        
        }
    }
    .info{
        font-size: 33px;
    }

    .number{
        font-size: 50px;
        font-weight: bold;
    }

    span{
        font-size: 19px;
        transition: all 0.4s;
        &:hover{
            cursor: pointer;
            color: $orange;
        }
    }
    .dc-button{
        margin-top: 70px ;
        padding: 15px 50px;
        background-color: $orange;
        color: $white;
        border-radius: 10px;
        border: none;
        transition: all 0.3s;
        &:hover{
            background-color: #DA5107;
        }
    }

</style>