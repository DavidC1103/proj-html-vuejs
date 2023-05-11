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
            <div class="d-flex justify-content-center align-items-center">
                <img src="../assets/img/avada-marketing-logo.png" alt="">
                <div class="h-100 align-items-center d-flex">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0 align-items-center">
                        <li class="nav-item-dc dropdown">
                            <a class="nav-link dc-link text-center">Home<i class="fa-solid fa-chevron-down"></i></a>
                            <ul class="dropdown-menu">
                                <li class="dropdown-item">Home Alternate</li>
                            </ul>
                        </li>
                        <li class="nav-item-dc dropdown">
                            <a class="nav-link dc-link">Services<i class="fa-solid fa-chevron-down"></i></a>
                            <div class="dropdown-menu p-0 dc-dropdown">
                                <div class="row h-100 m-0">
                                    <div class="col-4 p-4">
                                        <span class="fs-5">What We Do</span>
                                        <ul class="mt-4">
                                            <li class="d-flex">
                                                <div>
                                                    <i class="fa-brands fa-pix dc-i-blue"></i>
                                                </div>
                                                <div class="text-dropdown-first-col">
                                                    <span class="d-block fs-5">Strategic Marketin Plan</span>
                                                    <span>Maecenas ut erat lalesuada tortor dattis scelerisque eu ut ventis</span>
                                                </div>
                                            </li>
                                            <li class="d-flex">
                                                <div>
                                                    <i class="fa-brands fa-connectdevelop dc-i-yellow"></i>
                                                </div>
                                                <div class="text-dropdown-first-col">
                                                    <span class="d-block fs-5">Strategic Marketin Plan</span>
                                                    <span>Maecenas ut erat lalesuada tortor dattis scelerisque eu ut ventis</span>
                                                </div>
                                            </li>
                                            <li class="d-flex">
                                                <div>
                                                    <i class="fa-brands fa-hornbill dc-i-green"></i>
                                                </div>
                                                <div class="text-dropdown-first-col">
                                                    <span class="d-block fs-5">Strategic Marketin Plan</span>
                                                    <span>Maecenas ut erat lalesuada tortor dattis scelerisque eu ut ventis</span>
                                                </div>
                                            </li>
                                        </ul>
                                    </div>
                                    <div class="col-4 dc-bg p-4 ">
                                        <img src="https://avada.website/marketing-consultant/wp-content/uploads/sites/142/2020/07/about-team-intro-scaled.jpg" alt="">
                                        <div>
                                            <span class="d-block fs-5 mt-3 mb-2">How It Works ?</span>
                                            <span>Sed tincidunt tempor leo, vitae consequat lorem ornare fringilla ultricies pharetra.</span>
                                        </div>
                                        <div>
                                            <button class="dc-button-2">Explore More</button>
                                        </div>

                                    </div>
                                    <div class="col-4 dc-bg p-4">
                                        <ul>
                                            <li class="fw-bold mb-4">Resources</li>
                                            <li class="mt-2 mb-0"><span>Learning Center</span></li>
                                            <li class="mt-2 mb-0"><span>Video Tutorials</span></li>
                                            <li class="mt-2 mb-0"><span>Customers</span></li>
                                            <li class="mt-2 mb-0"><span>Blog</span></li>
                                        </ul>
                                        <div class="cta-2">
                                            <span>Are looking for custom service?</span>
                                            <span><i class="fa-solid fa-phone"></i> Get A Callback</span>
                                        </div>
                                    </div>
                                </div>

                            
                            </div>
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
                        <li class="nav-item-dc mb-5">
                            <button class="dc-button nav-link mb-4"><span>Free Quote</span></button>
                        </li>                  
                    </ul>
                </div>
            </div>
        </nav>
    </header>

  <jumbotron/>
</template>

<style lang="scss">
@use'../scss/partials/palette' as *;
    header{
        height: 100px;
        
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
                    padding: 10px;
                    top: 40px;
                    border: 0;
                    box-shadow: 0px 0px 1px 0px rgba(0, 0,0, 0.1);
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
                    .dropdown-menu{
                        display: block ;
                    }
                    .fa-chevron-down{
                        color: $orange;
                    }
                }
                .dc-dropdown{
                    position: absolute;
                    width: 1332px;
                    left: -365px;
                    z-index: 9999;
                    border-radius: 10px;
                    ul{
                        list-style: none;
                        padding-left: 0;
                        li{
                            margin-top: 10px;
                            margin-bottom: 30px;
                            .text-dropdown-first-col{
                                margin-left: 15px;
                            }
                        }
                    }
                    span{
                        font-size: 15px;
                    }
                    .dc-button-2{
                        margin-top: 15px ;
                        padding: 7px 20px;
                        background-color: $orange;
                        color: $white;
                        border-radius: 10px;
                        border: none;
                        transition: all 0.3s;
                        &:hover{
                            background-color: #DA5107;
                        }
                    }
                    .cta-2{
                        background-color: $white;
                        padding: 10px 20px;
                        display: flex;
                        border-radius: 10px;
                        margin-top: 150px;
                        span{
                            font-size: 13px;
                            &:last-child{
                                color: $orange;
                            }
                        }
                    }
                    .col-4:last-child{
                        border-left: 1px solid lightgrey;
                    }
                    .dc-bg{
                        background-color: $off-white;
                        border-radius: 0px 10px 10px 0px ;
                        img{
                            width: 400px;
                            border-radius: 15px;
                        }
                    }
                    .dc-i-blue{
                        color: $blue;
                        background-color: #EBF3FF;
                        padding: 10px;
                        border-radius: 50%;
                        font-size: 35px;
                    }
                    .dc-i-yellow{
                        color: $yellow;
                        background-color: #FEF8DF;
                        padding: 10px;
                        border-radius: 50%;
                        font-size: 35px;
                    }
                    .dc-i-green{
                        color: $green;
                        background-color: #E3F7EC;
                        padding: 10px;
                        border-radius: 50%;
                        font-size: 35px;
                    }
                }
            }
            .nav-item-dc{
                margin-left: 30px;
                display: flex;
                align-items: center;
                .nav-link{
                    &:hover{
                        color: $orange;
                        cursor: pointer;
                    }
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

                }
                
            }



            /*BOTTONE*/
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

            /*GENERALI HEADER*/
            .fa-phone{
                margin-left: 10px;
                color: $orange;
            }
            
            .navbar-nav{
                --bs-nav-link-color: $black;
            }
        }
    }
</style>