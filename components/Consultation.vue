<template>
  <div class="consultation">
    <div class="consultation__container container-product">
      <div class="consultation__container__consultant">
        <BlockConsultant/>
      </div>
      <div class="consultation__container__text-button">
        <div class="consultation__container__text-button__title">
            <p>Персональный</p>
        </div>
        <div class="consultation__container__text-button__subtitle">
            <p>Консультант на связи!</p>
        </div>
        <div class="consultation__container__text-button__text">
            <p>Когда Вы совершаете покупки на сайте “AudioFree” - все Ваши заказы ведет личный менеджер, который поможет с выбором и оформлением заказа.</p>
        </div>
        <div class="consultation__container__text-button__end">
            <p>Приятных и безопасных покупок!</p>
        </div>
        <div class="consultation__container__text-button__back-green"></div>
        <div class="consultation__container__text-button__button">
            <BlockConsultationButton/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

import BlockConsultant from "@/components/blocks/BlockConsultant"
import BlockConsultationButton from "@/components/blocks/BlockConsultationButton"

export default {
    components: {
        BlockConsultant,
        BlockConsultationButton
    }
}
</script>

<style lang="scss" scoped>
    .consultation{
        display: flex;
        height: 616px;
        background: #8B75C8;
        overflow: hidden;
        &__container{
            display: flex;
            flex-direction: row;
            &__consultant{
                display: flex;
                margin: 42px 0px 0px 0px;
            }
            &__text-button{
                display: flex;
                flex-direction: column;
                margin: 70px 0px 0px 610px;
                color: #FFFFFF;
                font-family: Roboto;
                font-style: normal;
                &__title{
                    display: flex;
                    font-weight: 300;
                    font-size: 44px;
                    line-height: 53px;
                    margin: 17px 0px 0px 0px;
                }
                &__subtitle{
                    display: flex;
                    font-weight: 600;
                    font-size: 45px;
                    line-height: 53px;
                    margin: 0px 0px 0px 0px;
                }
                &__text{
                    display: flex;
                    font-size: 24px;
                    font-weight: 300;
                    line-height: 30px;
                    margin: 25px 0px 0px 0px;
                }
                &__end{
                    display: flex;
                    font-size: 24px;
                    line-height: 53px;
                    margin: 282px 0px 0px -1px;
                    font-weight: 500;
                    position: absolute;
                    z-index: 3;
                    white-space: nowrap;
                }
                &__back-green{
                    display: flex;
                    background-image: url("../components/blocks/Consultation/Rectangle 168.svg");
                    height: 15px;
                    width: 380px;
                    margin: 312px 0px 0px -1px;
                    position: absolute;
                    z-index: 1;
                    
                } 
                &__button{
                    display: flex;
                    margin: 110px 0px 0px 0px;
                }
            }
        }
    }
@media (max-width: 1685px) {
    .consultation{
        display: flex;
        height: 616px;
        background: #8B75C8;
        overflow: hidden;
        &__container{
            display: flex;
            flex-direction: row;
            &__consultant{
                display: flex;
                margin: 42px 0px 0px 0px;
            }
            &__text-button{
                display: flex;
                flex-direction: column;
                margin: 70px 0px 0px 610px;
                color: #FFFFFF;
                font-family: Roboto;
                font-style: normal;
                &__title{
                    display: flex;
                    width: 450px;
                    font-weight: 100;
                    font-size: 42px;
                    line-height: 53px;
                    margin: 17px 0px 0px 0px;
                }
                &__subtitle{
                    display: flex;
                    font-weight: 100;
                    font-size: 45px;
                    line-height: 53px;
                    margin: 0px 0px 0px 0px;
                }
                &__text{
                    display: flex;
                    font-size: 25px;
                    margin: 25px 0px 0px 0px;
                    letter-spacing: -1px;
                }
                &__end{
                    display: flex;
                    font-size: 24px;
                    line-height: 53px;
                    margin: 330px 0px 0px -1px;
                    font-weight: 600;
                    position: absolute;
                    z-index: 3;
                }
                &__back-green{
                    display: flex;
                    background-image: url("../components/blocks/Consultation/Rectangle 168.svg");
                    height: 15px;
                    width: 380px;
                    margin: 358px 0px 0px -1px;
                    position: absolute;
                    z-index: 1;
                    
                } 
                &__button{
                    display: flex;
                    margin: 80px 0px 0px 0px;
                }
            }
        }
    }    
}
@media (max-width: 1461px) {
    .consultation{
        display: flex;
        height: 616px;
        background: #8B75C8;
        overflow: hidden;
        &__container{
            display: flex;
            flex-direction: row;
            &__consultant{
                display: flex;
                margin: 42px 0px 0px 0px;
            }
            &__text-button{
                display: flex;
                flex-direction: column;
                margin: 70px 0px 0px 610px;
                color: #FFFFFF;
                font-family: Roboto;
                font-style: normal;
                &__title{
                    display: flex;
                    width: 450px;
                    font-weight: 100;
                    font-size: 42px;
                    line-height: 53px;
                    margin: 17px 0px 0px 0px;
                }
                &__subtitle{
                    display: flex;
                    font-weight: 100;
                    font-size: 45px;
                    line-height: 53px;
                    margin: 0px 0px 0px 0px;
                }
                &__text{
                    display: flex;
                    font-size: 25px;
                    margin: 25px 0px 0px 0px;
                    letter-spacing: -1px;
                }
                &__end{
                    display: flex;
                    font-size: 24px;
                    line-height: 53px;
                    margin: 330px 0px 0px -1px;
                    font-weight: 600;
                    position: absolute;
                    z-index: 3;
                }
                &__back-green{
                    display: flex;
                    background-image: url("../components/blocks/Consultation/Rectangle 168.svg");
                    height: 15px;
                    width: 380px;
                    margin: 358px 0px 0px -1px;
                    position: absolute;
                    z-index: 1;
                    
                } 
                &__button{
                    display: flex;
                    margin: 130px 0px 0px 0px;
                }
            }
        }
    }    
}
@media (max-width: 1360px) {
    .consultation{
        display: flex;
        height: 616px;
        background: #8B75C8;
        overflow: hidden;
        &__container{
            display: flex;
            flex-direction: row;
            &__consultant{
                display: flex;
                margin: 42px 0px 0px 0px;
            }
            &__text-button{
                display: flex;
                flex-direction: column;
                margin: 70px 0px 0px 610px;
                color: #FFFFFF;
                font-family: Roboto;
                font-style: normal;
                &__title{
                    display: flex;
                    width: 450px;
                    font-weight: 100;
                    font-size: 42px;
                    line-height: 53px;
                    margin: 17px 0px 0px 0px;
                }
                &__subtitle{
                    display: flex;
                    font-weight: 100;
                    font-size: 45px;
                    line-height: 53px;
                    margin: 0px 0px 0px 0px;
                }
                &__text{
                    display: flex;
                    font-size: 25px;
                    margin: 25px 0px 0px 0px;
                    letter-spacing: -1px;
                }
                &__end{
                    display: flex;
                    font-size: 24px;
                    line-height: 53px;
                    margin: 330px 0px 0px -1px;
                    font-weight: 600;
                    position: absolute;
                    z-index: 3;
                }
                &__back-green{
                    display: flex;
                    background-image: url("../components/blocks/Consultation/Rectangle 168.svg");
                    height: 15px;
                    width: 380px;
                    margin: 358px 0px 0px -1px;
                    position: absolute;
                    z-index: 1;
                    
                } 
                &__button{
                    display: flex;
                    margin: 180px 0px 0px 0px;
                }
            }
        }
    }    
}
@media (max-width: 1110px) {
    .consultation{
        display: flex;
        height: 616px;
        background: #8B75C8;
        overflow: hidden;
        &__container{
            display: flex;
            flex-direction: row;
            &__consultant{
                display: flex;
                margin: 42px 0px 0px 0px;
            }
            &__text-button{
                display: flex;
                flex-direction: column;
                margin: 70px 0px 0px 550px;
                color: #FFFFFF;
                font-family: Roboto;
                font-style: normal;
                &__title{
                    display: flex;
                    width: 450px;
                    font-weight: 100;
                    font-size: 42px;
                    line-height: 53px;
                    margin: 17px 0px 0px 0px;
                }
                &__subtitle{
                    display: flex;
                    font-weight: 100;
                    font-size: 45px;
                    line-height: 53px;
                    margin: 0px 0px 0px 0px;
                }
                &__text{
                    display: flex;
                    font-size: 25px;
                    margin: 25px 0px 0px 0px;
                    letter-spacing: -1px;
                }
                &__end{
                    display: flex;
                    font-size: 24px;
                    line-height: 53px;
                    margin: 330px 0px 0px -1px;
                    font-weight: 600;
                    position: absolute;
                    z-index: 3;
                }
                &__back-green{
                    display: flex;
                    background-image: url("../components/blocks/Consultation/Rectangle 168.svg");
                    height: 15px;
                    width: 380px;
                    margin: 358px 0px 0px -1px;
                    position: absolute;
                    z-index: 1;
                    
                } 
                &__button{
                    display: flex;
                    margin: 100px 0px 0px 0px;
                }
            }
        }
    }    
}
@media (max-width: 768px) {
    .consultation{
        display: flex;
        height: 710px;
        background: #8B75C8;
        overflow: hidden;
        &__container{
            display: flex;
            flex-direction: column;
            &__consultant{
                display: flex;
                margin: 250px 0px 0px 200px;
                z-index: 3;
                position: absolute;
            }
            &__text-button{
                display: flex;
                flex-direction: column;
                margin: 30px 0px 0px 20px;
                color: #FFFFFF;
                font-family: Roboto;
                font-style: normal;
                align-items: center;
                &__title{
                    display: flex;
                    width: 250px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 300;
                    font-size: 30px;
                    line-height: 28px;
                    text-align: center;
                    margin: 17px 0px 0px 0px;
                }
                &__subtitle{
                    display: flex;
                    font-weight: 300;
                    font-size: 30px;
                    line-height: 28px;
                    margin: 0px 0px 0px 0px;
                }
                &__text{
                    display: flex;
                    font-size: 25px;
                    margin: 15px 0px 0px 0px;
                    letter-spacing: -1px;
                    text-align: center;
                }
                &__end{
                    display: flex;
                    font-size: 24px;
                    line-height: 53px;
                    margin: 165px 0px 0px -1px;
                    font-weight: 600;
                    position: absolute;
                    z-index: 3;
                }
                &__back-green{
                    display: flex;
                    background-image: url("../components/blocks/Consultation/Rectangle 168.svg");
                    height: 15px;
                    width: 384px;
                    margin: 196px 0px 0px -1px;
                    position: absolute;
                    z-index: 1;
                    
                } 
                &__button{
                    display: flex;
                    margin: 395px 0px 0px 0px;
                    z-index: 4;
                }
            }
        }
    }    
}
@media (max-width: 414px) {
    .consultation{
        display: flex;
        height: 710px;
        background: #8B75C8;
        overflow: hidden;
        &__container{
            display: flex;
            flex-direction: column;
            &__consultant{
                display: flex;
                margin: 250px 0px 0px 40px;
                z-index: 3;
                position: absolute;
            }
            &__text-button{
                display: flex;
                flex-direction: column;
                margin: 30px 0px 0px 20px;
                color: #FFFFFF;
                font-family: Roboto;
                font-style: normal;
                align-items: center;
                &__title{
                    display: flex;
                    width: 250px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 300;
                    font-size: 30px;
                    line-height: 28px;
                    text-align: center;
                    margin: 17px 0px 0px 0px;
                }
                &__subtitle{
                    display: flex;
                    font-weight: 300;
                    font-size: 30px;
                    line-height: 28px;
                    margin: 0px 0px 0px 0px;
                }
                &__text{
                    display: flex;
                    font-size: 20px;
                    margin: 14px 0px 0px 0px;
                    letter-spacing: -1px;
                    font-weight: 300;
                    text-align: center;
                }
                &__end{
                    display: flex;
                    font-size: 20px;
                    line-height: 53px;
                    margin: 184px 0px 0px -1px;
                    font-weight: 600;
                    position: absolute;
                    z-index: 3;
                }
                &__back-green{
                    display: flex;
                    background-image: url("../components/blocks/Consultation/Rectangle 168.svg");
                    height: 10px;
                    width: 320px;
                    margin: 212px 0px 0px -1px;
                    position: absolute;
                    z-index: 1;
                    
                } 
                &__button{
                    display: flex;
                    margin: 380px 0px 0px 0px;
                    z-index: 4;
                }
            }
        }
    }    
}
@media (max-width: 375px) {
    .consultation{
        display: flex;
        height: 709px;
        background: #8B75C8;
        overflow: hidden;
        &__container{
            display: flex;
            flex-direction: column;
            &__consultant{
                display: flex;
                margin: 250px 0px 0px 40px;
                z-index: 3;
                position: absolute;
            }
            &__text-button{
                display: flex;
                flex-direction: column;
                margin: 30px 0px 0px 0px;
                color: #FFFFFF;
                font-family: Roboto;
                font-style: normal;
                align-items: center;
                &__title{
                    display: flex;
                    width: 250px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 300;
                    font-size: 24px;
                    line-height: 28px;
                    text-align: center;
                    margin: 0px 0px 0px 92px;
                }
                &__subtitle{
                    display: flex;
                    font-weight: 300;
                    font-size: 24px;
                    line-height: 28px;
                    margin: 1px 0px 0px 5px;
                }
                &__text{
                    display: flex;
                    font-size: 15px;
                    margin: 13px 0px 0px 10px;
                    letter-spacing: 0px;
                    font-weight: 300;
                    line-height: 24px;
                    width: 335px;
                    font-size: 16px;
                    text-align: center;
                }
                &__end{
                    display: flex;
                    font-size: 16px;
                    line-height: 53px;
                    margin: 165px 0px 0px 12px;
                    font-weight: 600;
                    position: absolute;
                    z-index: 3;
                }
                &__back-green{
                    display: flex;
                    background-image: url("../components/blocks/Consultation/Rectangle 168.svg");
                    height: 14px;
                    width: 266px;
                    margin: 191px 0px 0px 16px;
                    position: absolute;
                    z-index: 1;
                    
                } 
                &__button{
                    display: flex;
                    margin: 380px 0px 0px 15px;
                    z-index: 4;
                }
            }
        }
    }    
}
@media (max-width: 360px) {
    .consultation{
        display: flex;
        height: 709px;
        background: #8B75C8;
        overflow: hidden;   
        &__container{
            display: flex;
            flex-direction: column;
            &__consultant{
                display: flex;
                margin: 250px 0px 0px 20px;
                z-index: 3;
                position: absolute;
            }
            &__text-button{
                display: flex;
                flex-direction: column;
                margin: 30px 0px 0px -20px;
                color: #FFFFFF;
                font-family: Roboto;
                font-style: normal;
                align-items: center;
                &__title{
                    display: flex;
                    width: 250px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 300;
                    font-size: 25px;
                    line-height: 28px;
                    text-align: center;
                    margin: 0px 0px 0px 96px;
                }
                &__subtitle{
                    display: flex;
                    font-weight: 300;
                    font-size: 25px;
                    line-height: 28px;
                    margin: 0px 0px 0px 26px;
                }
                &__text{
                    display: flex;
                    font-size: 15px;
                    margin: 13px 0px 0px 33px;
                    letter-spacing: 1px;
                    font-weight: 300;
                    line-height: 25px;
                    width: 320px;
                    text-align: center;
                }
                &__end{
                    display: flex;
                    font-size: 16px;
                    line-height: 53px;
                    margin: 165px 0px 0px 12px;
                    font-weight: 600;
                    position: absolute;
                    z-index: 3;
                }
                &__back-green{
                    display: flex;
                    background-image: url("../components/blocks/Consultation/Rectangle 168.svg");
                    height: 14px;
                    width: 266px;
                    margin: 191px 0px 0px 16px;
                    position: absolute;
                    z-index: 1;
                    
                } 
                &__button{
                    display: flex;
                    margin: 376px 0px 0px 20px;
                    z-index: 4;
                }
            }
        }
    }    
}
</style>