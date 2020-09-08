<template>
  <div class="advantage">
      <div class="advantage__container container-product">
        <div class="advantage__container__title">
            <p><a>Чем беспроводные лучше?</a></p>
            <p>Все о преимуществах наушников Bluetooth</p>
        </div>
        <div class="advantage__container__blocks-advantage">
            <BlockAdvantageLeft class="advantage__container__blocks-advantage__left display-none"/> 
            <BlockAdvantageCenter class="advantage__container__blocks-advantage__center"/> 
            <BlockAdvantageRight class="advantage__container__blocks-advantage__right display-none"/>
      </div>
      <div class="mob-advantage">
          <BlockAdvantageMob/>
      </div>
    </div>
  </div>
</template>

<script>

import BlockAdvantageLeft from "@/components/blocks/BlockAdvantageLeft"
import BlockAdvantageRight from "@/components/blocks/BlockAdvantageRight"
import BlockAdvantageCenter from "@/components/blocks/BlockAdvantageCenter"
import BlockAdvantageMob from "@/components/blocks/BlockAdvantageMob"

export default {
    components: {
        BlockAdvantageLeft,
        BlockAdvantageCenter,
        BlockAdvantageRight,
        BlockAdvantageMob
    }
}
</script>

<style lang="scss" scoped>
    .advantage{
        display: flex;
        height: 798px;
        width: 100%;
        background-color: #8B75C8;
        &__container{
            display: flex;
            flex-direction: column;
            &__title{
                margin: 110px 0px 0px -44px;
                display: flex;
                flex-direction: column;
                font-family: Roboto;
                font-style: normal;
                font-weight: 400;
                font-size: 44px;
                line-height: 52px;
                text-align: center;
                color: #FFFFFF;
                p{
                    margin: 0px 0px 0px 0px;
                    a{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: 300;
                    }
                }
            }
            &__blocks-advantage{
                margin: 35px 0px 0px 0px;
                display: flex;
                flex-direction: row;
                width: 100%;
                &__left{
                    display: flex;
                    margin: 0px 0px 0px 0px;
                }
                &__center{
                    display: flex;
                    margin: -5px 0px 0px -50px;
                }
                &__right{
                    display: flex;
                    margin: 0px 0px 0px 550px;
                }                
            }
        }
    }
    .mob-advantage{
        display: none;
    }
   @media (max-width: 1440px) {
    .advantage{
        display: flex;
        height: 798px;
        width: 100%;
        background-color: #8B75C8;
        &__container{
            display: flex;
            flex-direction: column;
            &__title{
                margin: 110px 0px 0px -45px;
                display: flex;
                flex-direction: column;
                font-family: Roboto;
                font-style: normal;
                font-weight: 300;
                font-size: 44px;
                line-height: 52px;
                text-align: center;
                color: #FFFFFF;
                p{
                    margin: 0px 0px 0px 0px;
                    a{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: 100;
                    }
                }
            }
            &__blocks-advantage{
                margin: 35px 0px 0px -30px;
                display: flex;
                flex-direction: row;
                width: 100%;
                &__left{
                    display: flex;
                    margin: 0px 0px 0px 0px;
                }
                &__center{
                    display: flex;
                    margin: -5px 0px 0px -50px;
                }
                &__right{
                    display: flex;
                    margin: 0px 0px 0px 550px;
                }                
            }
        }
    }
   }
    .mob-advantage{
        display: none;
    }
   @media (max-width: 1320px) {
    .advantage{
        display: flex;
        height: 1498px;
        width: 100%;
        background-color: #8B75C8;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 0px 0px 0px 100px;
            &__title{
                margin: 110px 0px 0px -45px;
                display: flex;
                flex-direction: column;
                font-family: Roboto;
                font-style: normal;
                font-weight: 300;
                font-size: 44px;
                line-height: 52px;
                text-align: center;
                color: #FFFFFF;
                p{
                    margin: 0px 0px 0px 0px;
                    a{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: 100;
                    }
                }
            }
            &__blocks-advantage{
                margin: 35px 0px 0px -30px;
                display: flex;
                flex-direction: row;
                width: 100%;
                &__left{
                    display: none;
                }
                &__center{
                    display: flex;
                    margin: -5px 0px 0px 200px;
                }
                &__right{
                   display: none;
                }                
            }
        }
    }
    .display-none{
        display: none;
    }
    .mob-advantage{
        display: flex;
        margin: 480px 0px 0px 230px;
    }
}
   @media (max-width: 1320px) {
    .advantage{
        display: flex;
        height: 1498px;
        width: 100%;
        background-color: #8B75C8;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 0px 0px 0px 0px;
            &__title{
                margin: 50px 0px 0px 30px;
                display: flex;
                flex-direction: column;
                font-family: Roboto;
                font-style: normal;
                font-weight: 300;
                font-size: 44px;
                line-height: 52px;
                text-align: center;
                color: #FFFFFF;
                p{
                    margin: 0px 0px 0px 0px;
                    a{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: 100;
                    }
                }
            }
            &__blocks-advantage{
                margin: 35px 0px 0px -30px;
                display: flex;
                flex-direction: row;
                width: 100%;
                &__left{
                    display: none;
                }
                &__center{
                    display: flex;
                    margin: -5px 0px 0px 200px;
                }
                &__right{
                   display: none;
                }                
            }
        }
    }
    .display-none{
        display: none;
    }
    .mob-advantage{
        display: flex;
        margin: 480px 0px 0px 230px;
    }
}
   @media (max-width: 414px) {
    .advantage{
        display: flex;
        height: 1250px;
        width: 100%;
        background-color: #8B75C8;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 0px 0px 0px 0px;
            &__title{
                margin: 50px 0px 0px 30px;
                width: 370px;
                display: flex;
                flex-direction: column;
                font-family: Roboto;
                font-style: normal;
                font-weight: 300;
                font-size: 24px;
                line-height: 28px;
                text-align: center;
                p{
                    margin: 0px 0px 0px 0px;
                    a{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: 100;
                    }
                }
            }
            &__blocks-advantage{
                margin: 35px 0px 0px -30px;
                display: flex;
                flex-direction: row;
                width: 100%;
                &__left{
                    display: none;
                }
                &__center{
                    display: flex;
                    margin: -5px 0px 0px 100px;
                }
                &__right{
                   display: none;
                }                
            }
        }
    }
    .display-none{
        display: none;
    }
    .mob-advantage{
        display: flex;
        margin: 280px 0px 0px 30px;
    }
}
   @media (max-width: 375px) {
    .advantage{
        display: flex;
        height: 1250px;
        width: 100%;
        background-color: #8B75C8;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 0px 0px 0px 0px;
            &__title{
                margin: 35px 0px 0px 2px;
                width: 370px;
                display: flex;
                flex-direction: column;
                font-family: Roboto;
                font-style: normal;
                font-weight: 400;
                font-size: 24px;
                line-height: 28px;
                text-align: center;
                p{
                    a{
                        margin: 0px 0px 0px 3px;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: 300;
                    }
                }
            }
            &__blocks-advantage{
                margin: 22px 0px 0px -56px;
                display: flex;
                //justify-content: space-between;
                flex-direction: row;
                width: 100%;
                &__left{
                    display: none;
                }
                &__center{
                    display: flex;
                    margin: -5px 0px 0px 100px;
                }
                &__right{
                   display: none;
                }                
            }
        }
    }
    .display-none{
        display: none;
    }
    .mob-advantage{
        display: flex;
        margin: 236px 0px 0px 18px;
    }
}
</style>