<script>
import jumbotron from '../components/partials/jumbotron.vue'
export default{
    components:{
        jumbotron
    }
}
</script>

<template>
    <header>
        <nav class="navbar navbar-expand container-fluid h-100">
            <div class="d-flex justify-content-center align-items-center h-100">
                <img src="../assets/img/avada-marketing-logo.png" alt="">
                <div class="h-100 align-items-center d-flex">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0 h-100 align-items-center">
                        <li class="nav-item-dc dropdown">
                            <a class="nav-link dc-link text-center">Home<i class="fa-solid fa-chevron-down"></i></a>
                            <ul class="dropdown-menu">
                                <li class="dropdown-item">Home Alternate</li>
                            </ul>
                        </li>
                        <li class="nav-item-dc dropdown">
                            <a class="nav-link dc-link">Services<i class="fa-solid fa-chevron-down"></i></a>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item">Action</a></li>
                            </ul>
                        </li>
                        <li class="nav-item-dc">
                            <a class="nav-link dc-link">Why Us</a>
                        </li>
                        <li class="nav-item-dc">
                            <a class="nav-link dc-link">Case Studies</a>
                        </li>
                        <li class="nav-item-dc">
                            <a class="nav-link dc-link">About</a>
                        </li>
                        <li class="nav-item-dc">
                            <a class="nav-link dc-link">Blog</a>
                        </li>
                        <li class="nav-item-dc d-flex">
                            <span class="nav-link"><i class="fa-solid fa-phone"></i></span>
                            <span class="nav-link">(555) 802-1234 </span>
                        </li>
                        
                            <button class="dc-button nav-link"><span>Free Quote</span></button>
                        
                       
                        
                    </ul>
                </div>
            </div>
        </nav>
    </header>
    
  <jumbotron/>
</template>

<style lang="scss">
@use'../scss/main.scss' as *;
    header{
        height: 120px;
        nav{
            letter-spacing: 1px;
            font-size: 16px;
            font-weight: 600;

            .dropdown{
                position: relative;
                display: inline-block;
                transition: all 0.5s;
                .fa-chevron-down{
                    margin-left: 5px ;
                    font-size: 11px;
                    color: $black;
                }
                .dropdown-menu{
                    display: none;
                    position: absolute;
                    min-width: 250px;
                    top: 70px;
                    border: 0;
                    box-shadow: 0px 8px 16px 0px rgba(0, 0,0, 0.2);
                    z-index: 1;
                    &:hover{
                        background-color: none;
                    }
                    .dropdown-item{
                        display: block;
                        background-color: white;
                        &:hover{
                            color: $orange;
                        }
                    }
                }
                &:hover{
                    cursor: pointer;
                    .dropdown-menu{
                        display: block ;
                    }
                    .fa-chevron-down{
                        color: $orange;
                    }
                }
            }



            .nav-item-dc{
                margin-left: 30px;
                display: flex;
                align-items: center;
                height: 100%;
                .dc-link{
                    transition: all 0.1s;
                    &::after{
                        display: block;
                        content: '';
                        margin: 0 auto;
                        width: 0;
                        height: 2px;
                        background-color: $orange;
                        transition: width 0.3s;
                    }
                    &:hover::after{
                        width: 100%;
                    }
                    &:hover{
                        color: $orange;
                        cursor: pointer;
                    }
                }
            }

            .navbar-nav{
                --bs-nav-link-color: $black;
            }



            .dc-button{
                border-radius: 10px;
                background-color: $orange-faded;
                border: none;
                color: $orange;
                padding: 20px 25px;
                margin-left: 30px ;
                &:hover{
                    background-color: $orange;
                    color: $white;
                }
                span{
                    padding: 20px 25px;
                }
            }
            .fa-phone{
                margin-left: 10px;
                color: $orange;
            } 
        }
    }
</style>