<script>
export default{
    
}
</script>

<template>
    <div class="jumbo">
        <div class="container">
            <div class="row g-5">
                <div class="col-6 text-white">
                    <div class="left-col">
                        <h1>Unlock Your Online Growth Potential</h1>
                        <span>Online marketing to secure customer retention, leads, and sales. We focus on the bigger picture.</span>
                        <div><button>Our Services <i class="fa-solid fa-arrow-right"></i></button></div>
                    </div>
                </div>
                <div class="col-6">
                    <div class="right-col text-center">
                        <img src="../../assets/img/marketing-consultant-expert.jpg" alt="" class="expert">
                        <div class="mt-3"><h3>Richard Madsen</h3></div>
                        <div class="mt-3"><h5>Marketing Consultant Expert</h5></div>
                        <div class="mt-3 phone">
                            <span><i class="fa-solid fa-phone me-3"></i></span>
                            <span>(555) 802-1234 </span>
                        </div>
                        <input type="text" placeholder="Your Name*" class="w-100 mt-3">
                        <input type="text" placeholder="Your Email*" class="w-100 mt-3">
                        <input type="text" placeholder="Your Phone Number*" class="w-100 mt-3">
                        <button class="w-100 mt-3 mb-3">Get A Callback</button>
                        <span class="accept-conditions">By submitting my data I agree to be contacted</span>


                    </div>
                </div>
            </div>

        </div>

    </div>
</template>

<style lang="scss">
@use '../../scss/partials/palette' as *;
    .jumbo{
        margin-top: 60px;
        min-height: 680px;
        background-image: url('../../assets/img/marketing-intro.jpg');
        background-position: center;
        background-size: cover;
        .col-6{
            position: relative;
            margin-top: 100px;
            .left-col{
                h1{
                font-size: 73px;
                margin-bottom: 20px;
                }
                span{
                    font-size: 28px;
                }
                button{
                    margin-top: 50px;
                    padding: 15px 45px;
                    border: 2px solid $black;
                    border-radius: 9px;
                    background-color: $white;
                    font-size: 18px;
                    i{
                        margin-left: 10px;
                    }
                    &:hover{
                        background-color: transparent;
                        color: $white;
                        border-color: $white ;
                    }
                }
            }
        }
        .right-col{
            position: absolute;
            background-color: $white;
            height: 610px;
            width: 480px;
            top: 4px;
            right: 125px;
            z-index: 999;
            border-radius: 15px;
            box-shadow: 0px 2px 0px 0px rgba(0, 0,0, 0.1);
            padding: 20px;
            .expert{
                border-radius: 50%;
                width: 80px;
            }
            h5{
                color: $grey;
            }
            .phone{
                color: $orange;
                font-size: 18px;
            }

            input{
                padding: 20px;
                border: 1px solid rgba(128, 128, 128, 0.39);
                border-radius: 15px ;
                &:hover{
                    border-color: #fa935c;
                }
                &:focus-visible{
                    border-color: $orange;
                }
            }
            button{
                padding: 15px;
                background-color: $orange;
                color: $white;
                border-radius: 15px;
                border: none;
                &:hover{
                    background-color: #DA5107;
                }

            }
            .accept-conditions{
                color: $grey;
                font-size: 13px;
            }

        }
    }

</style>