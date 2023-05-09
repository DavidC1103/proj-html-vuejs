<script>
export default{
    
}
</script>

<template>
    <div class="jumbo">
        <div class="container">
            <div class="row g-5">
                <div class="col-6 text-white">
                    <h1>Unlock Your Online Growth Potential</h1>
                    <span>Online marketing to secure customer retention, leads, and sales. We focus on the bigger picture.</span>
                    <div><button>Our Services <i class="fa-solid fa-arrow-right"></i></button></div>
                </div>
                <div class="col-6"></div>
            </div>

        </div>

    </div>
</template>

<style lang="scss">
@use '../../scss/partials/palette' as *;
    .jumbo{
        position: relative;
        margin-top: 60px;
        min-height: 680px;
        background-image: url('../../assets/img/marketing-intro.jpg');
        background-position: center;
        background-size: cover;
        filter: grayscale(30%);
        .col-6{
            margin-top: 100px;
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

</style>