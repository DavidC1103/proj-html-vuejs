<script>
export default {
    
}
</script>

<template>
    <div class="dc-bg-color-2">
        <div class="container">
            <div class="row">
                <div class="col-6 text-white reveal fade-left">
                    <h2>Let’s Make Things Happen</h2>
                    <p class="dc-p">Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</p>
                    <p class="mb-4">“The team at Avada Marketing Consultant is fabulous. They helped us unlock our potential online and offline. We have experienced year on year growth due to their progressive approach.”</p>
                    <span class="d-block">George Anderson</span>
                    <span class="dc-span">Digitalbox CEO</span>
                </div>
                <div class="col-6 reveal">
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
    .dc-bg-color-2{
        padding: 150px;
        margin-bottom: 120px;
        background-color: $black;
        h2{
            font-size: 70px;
        }
        .dc-p{
            font-size: 32px;
            &::after{
                margin-top: 40px;
                margin-bottom: 40px;
                display: block;
                content: '';
                width: 100px;
                height: 1px;
                background-color: $grey;
            }
        }
        p{
            font-size: 23px;
            display: block;
        }
        .dc-span{
            font-size: 13px;
            color: $grey;
        }
        .right-col{
            background-color: $white;
            width: 480px;
            border-radius: 15px;
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
                transition: all 0.3s;
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