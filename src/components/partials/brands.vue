
<script>
export default {
    
}
</script>

<template>
    <div class="brands text-center ">
        <h2 class="reveal">Some Brands We Work With</h2>
        <span class="reveal">Quisque aliquet, libero consequat elementum convallis.</span>
        <div class="mt-5 brands-img">
            <img src="../../assets/img/abstract.png" alt="" class="reveal fade-left">
            <img src="../../assets/img/cglobal.png" alt="" class="reveal fade-left">
            <img src="../../assets/img/next.png" alt="" class="reveal fade-left">
            <img src="../../assets/img/hemisferio.png" alt="" class="reveal fade-right">
            <img src="../../assets/img/spaces.png" alt="" class="reveal fade-right">
            <img src="../../assets/img/digitalbox.png" alt="" class="reveal fade-right">
        </div>

    </div>
  
</template>

<style lang="scss">
    .brands{
        margin-top: 150px;
        h2{
            font-size: 55px;
            margin-bottom: 10px;
        }
        span{
            font-size: 24px;
        }

        .brands-img{
            img{
                width: 150px;
                margin-right: 80px;
                &:last-child{
                    margin-right: 0px;
                }
            }
        }


    }

</style>