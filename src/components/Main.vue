<script>
import brands from './partials/brands.vue'
import expert from './partials/expert-main.vue'
import cards from './partials/cards.vue'
import WorkWithUs from './partials/work-with-us.vue'

export default{
    components:{
        brands,
        expert,
        cards,
        WorkWithUs,
    }
}
</script>

<template>
    <main class="container mt-5">
        <div class="row">
            <div class="col-6">
                <img src="../assets/img/image.png" alt="">
            </div>
            <div class="col-4 mt-5">
                <span>Business Growth</span>
                <h2>Increase Brand Awareness</h2>
                <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis gravida et at massa.</span>
                <button class="dc-button">Get A Consultation</button>
            </div>
            <div class="dc-margin"></div>
            <div class="col-4">
                <span>Investors In People</span>
                <h2>In-House Sales Training</h2>
                <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis gravida et at massa.</span>
                <button class="dc-button">Get A Consultation</button>
            </div>
            <div class="col-4">
                <img src="../assets/img/image (1).png" alt="">
            </div>
            <div class="dc-margin"></div>
            <div class="col-6">
                <img src="../assets/img/image (2)(1).png" alt="">
            </div>
            <div class="col-4">
                <span>Social Media Analysis</span>
                <h2>Harness Your Social Proof</h2>
                <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis gravida et at massa.</span>
                <button class="dc-button">Get A Consultation</button>

            </div>
        </div>
    </main>

    <!--BRANDS-->
    <brands/>

    <!--EXPERT ON MAIN-->
    <expert/>

    <cards/>

    <Work-With-Us/>
  
</template>

<style lang="scss"> 
@use'../scss/partials/palette' as *;
    main{
        h2{
            font-size: 60px;
            margin-top: 10px;
            margin-bottom: 20px;
        }
        span{
            line-height: 2.2rem;
            font-size: 23px;
        }

        .row{
            margin-top: 100px;
            .dc-button{
                margin-top: 40px ;
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
        }

        .dc-margin{
            margin: 150px 0px ;
        }

    }


</style>