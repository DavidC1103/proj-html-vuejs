<script>
import Awards from './awards.vue'
export default{
    components:{
        Awards
    }
    
    
}
</script>

<template>
    <div class="dc-bg-color">
        <div class="container">
            <div class="row">
                <div class="col-5 mt-5">
                    <h2>We Boost Our Clients’ Bottom Line by Optimizing Their Growth Potential.</h2>
                    <span>Quisque aliquet, libero consequat elementum convallis, erat risus imperdiet pellentesque sem neque eget.</span>
                    <div>
                        <button class="dc-button">Why Work Whit Us</button>
                    </div>
                </div>
                <div class="col-5">
                    <img src="../../assets/img/we-boost-our-clients-600x549.jpg" alt="">
                </div>
                <div class="dc-margin"></div>
                <div class="col-5">
                    <h3 class="mb-3 fs-2">We Build Relationships</h3>
                    <span class="fs-5 mb-5">Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</span>
                    <h3 class="mt-5 fs-2">Proprietary Processes</h3>
                    <span class="fs-5">Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</span>
                </div>
                <div class="col-5">
                    <div class="ms-0">
                        <div class="d-flex align-items-center mb-5">
                            <img src="../../assets/img/image (2).png" alt="" class="me-4 ms-4">
                            <div class="ms-0">
                                <div class="fs-3 mb-3">Accountability </div>
                                <span class="fs-5">Curabitur ac leo nunc vestibulum</span>
                            </div>
                        </div>
                        <div class="d-flex align-items-center mb-5">
                            <img src="../../assets/img/image (3).png" alt="" class="ms-4 me-4">
                            <div class="ms-0">
                                <div class="fs-4 mb-3">Transparency</div>
                                <span class="fs-5">Curabitur ac leo nunc vestibulum</span>
                            </div>
                        </div>
                        <div class="d-flex align-items-center mb-5">
                            <img src="../../assets/img/image (4).png" alt="" class="ms-4 me-4">
                            <div class="ms-0">
                                <div class="fs-3 mb-3">Investment</div>
                                <span class="fs-5">Curabitur ac leo nunc vestibulum</span>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
            
            <Awards/>
        </div>
    </div>
  
</template>

<style lang="scss">
@use '../../scss/partials/palette' as *;

    .dc-bg-color{
        padding: 150px;
        margin-top: 130px;
        background-color: $off-white;
        h2{
            font-size: 55px;
            margin-bottom: 35px;
        }
        span{
            font-size: 26px;
        }

        img{
            border-radius: 10px;
        }
        .dc-button{
            margin-top: 30px ;
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
        .dc-margin{
            margin-top: 100px;
            margin-bottom: 50px;
        }
    }


</style>