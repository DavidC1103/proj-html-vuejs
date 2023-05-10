<script>
export default {
    
}
</script>

<template>
    <div class="dc-bg-color">
        <div class="container">
            <div class="row">
                <div class="col-6 ms-0 mb-5">
                    <h2>Marketing Resources: Insider Advice on How to Increase Online Sales</h2>
                </div>
                <div class="col-5 d-flex justfify-content-end align-items-end me-3 mb-5">
                    <div class="me-0 mb-5">
                        <button class="dc-button">Explore All Resources</button>
                    </div>
                </div>
                <div class="col-4">
                    <img src="../../assets/img/blog-posts-4-400x267.jpg" alt="">
                    <div class="faded"></div>
                    <div class="mt-3"><span class="fs-2">Marketing Tips And Tricks For Your Website</span></div>
                </div>
                <div class="col-4">
                    <img src="../../assets/img/blog-posts-5-400x267.jpg" alt="">
                    <div class="faded"></div>
                    <div class="mt-3"><span class="fs-2">How to Write Stunning Blog Post Titles</span></div>
                    
                </div>
                <div class="col-4">
                    <img src="../../assets/img/blog-posts-6-400x267.jpg" alt="">
                    <div class="faded"></div>
                    <div class="mt-3"><span class="fs-2">Techniques to Reduce Facebook Ads Spend</span></div>

                </div>
                
            </div>
    
        </div>
    </div>
  
</template>

<style lang="scss">
@use '../../scss/partials/palette' as *;

.dc-bg-color{
    padding: 150px;
    margin-top: 130px;
    background-color: $off-white;
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
                bottom: 112px;
                height: 100%;
                border-radius: 10px;
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

</style>