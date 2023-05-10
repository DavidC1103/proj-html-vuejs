<script>
export default {
    
}
</script>

<template>
    <div class="container">
        <div class="cta d-flex align-items-center">
            <img src="../../assets/img/marketing-expert-cta.png" alt="" class="expert me-4 ms-2">
            <div class="ms-0">
                <div class="name">Sandy Reiff</div>
                <span class="role">Marketing Consultant Expert</span>
            </div>
            <div>
                <h3>Drive Leads and Sales with Avada</h3>
            </div>
            <div class="me-0">
                <button class="dc-button"><i class="fa-solid fa-phone me-2"></i> (555) 802-1234</button>
            </div>
        </div>

    </div>
  
</template>

<style lang="scss">
@use '../../scss/partials/palette' as *;
    .cta{
        margin-top: 100px;
        box-shadow: 0px 7px 10px 0px rgba(0, 0,0, 0.1);
        padding: 15px 40px;
        border-radius: 10px;
        .expert{
            border-radius: 50%;
            height: 60px;
        }
        .name{
            font-size: 19px;
        }
        .role{
            font-size: 13px;
        }
        .dc-button{
            border-radius: 10px;
            background-color: $orange-faded;
            border: none;
            color: $orange;
            padding: 15px 40px;
            &:hover{
                background-color: $orange;
                color: $white;
            }
        }
    }
    


</style>