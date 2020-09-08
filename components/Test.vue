<template>
  <div class="test">
    <div class="test__container container-product">
        <div>
            <div class="test__container__title-subtitle">
                <div class="test__container__title-subtitle__title">
                    <p>Подберем 5 лучших моделей <a>беспроводных наушников под Ваши цели</a></p>
                </div>
                <div class="test__container__title-subtitle__subtitle">
                    <p>Пройдите тест и получите <b><a>скидку до 10%</a> на первую покупку</b></p>
                </div>
            </div>
            <div class="test__container__title-subtitle__button">
                <BlockTestButton/>
            </div>
        </div>
        <div class="test__container__image">
            <BlockTestImage/>
        </div>
    </div>
  </div>
</template>

<script>

import BlockTestImage from "@/components/blocks/BlockTestImage"
import BlockTestButton from "@/components/blocks/BlockTestButton"

export default {
    components:{
        BlockTestButton,
        BlockTestImage
    }
}
</script>

<style lang="scss" scoped>
    .test{
        display: flex;
        height: 570px;
        background: #8B75C8;
        &__container{
            display: flex;
            justify-content: space-between;
            width: 100%;
            &__title-subtitle{
                display: flex;
                flex-direction: column;
                margin: 98px 0px 0px 6px;
                &__title{
                    display: flex;
                    width: 619px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 40px;
                    line-height: 48px;
                    color: #FFFFFF;
                    margin: 0px 0px 0px 0px;
                    a{
                        display: flex;
                        width: 530px;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: 300;
                        font-size: 40px;
                        line-height: 48px;
                        color: #FFFFFF;
                    }
                }
                &__subtitle{
                    display: flex;
                    width: 412px;
                    margin: 38px 0px 0px 0px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 20px;
                    line-height: 30px;
                    color: #FFFFFF;
                    a{
                        color: #97D413;
                    }
                }
                &__button{
                    margin: 50px 0px 0px 2px;
                }
            }
        }
        &__image{
            display: flex;
        }
    }
@media (max-width: 1320px) {
    .test{
        display: flex;
        height: 1070px;
        background: #8B75C8;
        &__container{
            display: flex;
            flex-direction: column; 
            margin: 0px 0px 0px 400px;
            width: 100%;
            &__title-subtitle{
                display: flex;
                flex-direction: column;
                margin: 98px 0px 0px 8px;
                &__title{
                    display: flex;
                    width: 619px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 100;
                    font-size: 40px;
                    line-height: 48px;
                    color: #FFFFFF;
                }
                &__subtitle{
                    display: flex;
                    width: 412px;
                    margin: 38px 0px 0px 0px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 20px;
                    line-height: 30px;
                    color: #FFFFFF;
                    a{
                        color: #97D413;
                    }
                }
                &__button{
                    margin: 570px 0px 0px 100px;
                    position: absolute;
                    z-index: 3;
                }
            }
            &__image{
                display: flex;
                margin: 320px 0px 0px 2px;
                position: absolute;
            }
        }
    }    
}
@media (max-width: 1050px) {
    .test{
        display: flex;
        height: 1070px;
        background: #8B75C8;
        &__container{
            display: flex;
            flex-direction: column; 
            margin: 0px 0px 0px 140px;
            width: 100%;
            &__title-subtitle{
                display: flex;
                flex-direction: column;
                margin: 98px 0px 0px 8px;
                &__title{
                    display: flex;
                    width: 619px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 100;
                    font-size: 40px;
                    line-height: 48px;
                    color: #FFFFFF;
                }
                &__subtitle{
                    display: flex;
                    width: 412px;
                    margin: 38px 0px 0px 0px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 20px;
                    line-height: 30px;
                    color: #FFFFFF;
                    a{
                        color: #97D413;
                    }
                }
                &__button{
                    margin: 570px 0px 0px 100px;
                    position: absolute;
                    z-index: 3;
                }
            }
            &__image{
                display: flex;
                margin: 320px 0px 0px 2px;
                position: absolute;
            }
        }
    }    
}
@media (max-width: 414px) {
    .test{
        display: flex;
        height: 682px;
        background: #8B75C8;
        &__container{
            display: flex;
            flex-direction: column; 
            margin: 0px 0px 0px 0px;
            width: 100%;
            &__title-subtitle{
                display: flex;
                flex-direction: column;
                margin: 50px 0px 0px 50px;
                &__title{
                    display: flex;
                    width: 500px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 24px;
                    line-height: 30px;
                    color: #FFFFFF;
                    text-align: center;
                    margin: 0px 0px 0px 0px;
                    a{
                        display: flex;
                        width: 300px;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: 300;
                        font-size: 24px;
                        line-height: 30px;
                        color: #FFFFFF;
                    }
                }
                &__subtitle{
                    display: flex;
                    width: 240px;   
                    margin: 30px 0px 0px 0px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 300;
                    font-size: 18px;
                    line-height: 24px;
                    text-align: center;
                    color: #FFFFFF;
                    a{
                        color: #97D413;
                    }
                    b{
                        white-space: nowrap;
                    }
                }
                &__button{
                    margin: 350px 0px 0px 40px;
                    position: absolute;
                    z-index: 3;
                }
            }
            &__image{
                display: flex;
                margin: 260px 0px 0px 20px;
                position: absolute;
            }
        }
    }    
}
@media (max-width: 375px) {
    .test{
        display: flex;
        height: 682px;
        background: #8B75C8;
        &__container{
            display: flex;
            flex-direction: column; 
            margin: 0px 0px 0px 0px;
            width: 100%;
            &__title-subtitle{
                display: flex;
                flex-direction: column;
                margin: 36px 0px 0px 21px;
                &__title{
                    display: flex;
                    width: 500px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 24px;
                    line-height: 30px;
                    text-align: center;
                    color: #FFFFFF;
                    a{
                        margin-left: 14px;
                        width: 300px;
                        display: flex;
                        font-weight: 300;
                    }
                }
                &__subtitle{
                    display: flex;
                    width: 245px;   
                    margin: 21px 0px 0px 13px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 300;
                    font-size: 18px;
                    line-height: 24px;
                    text-align: center;
                    color: #FFFFFF;
                    a{
                        color: #97D413;
                        margin: 0px 0px 0px 2px;
                        font-weight: 800;
                    }
                    b{
                        white-space: nowrap;
                        margin: 0px 0px 0px 5px;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: 300;
                    }
                }
                &__button{
                    margin: 363px 0px 0px 20px;
                    position: absolute;
                    z-index: 3;
                }
            }
            &__image{
                display: flex;
                margin: 250px 0px 0px 9px;
                position: absolute;
            }
        }
    }    
}
@media (max-width: 360px) {
    .test{
        &__container{
            margin: 0px 0px 0px -8px;
        }
    }    
}
</style>