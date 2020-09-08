<template>
  <div class="delivery">
    <div class="delivery__title">
        <BlockDeliveryTitleSubtitle/>
    </div>
    <div class="delivery__subtitle">
        <p>Текст о том, что мы не просто так подбираем наушники, а ассортимент формируется исходя из спроса и новинок рынка, с учетом требований к качеству и по наличию популярных, топовых, классических позиций</p>
    </div>
    <div class="delivery__cards container-product">
        <div class="delivery__cards__card">
            <div class="delivery__cards__card__image">
                <img src="../assets/image/delivery/delivery 1.svg" />
            </div>
            <div class="delivery__cards__card__title">
                <p>Доставка 1-2 дня</p>
            </div>
            <div class="delivery__cards__card__text">
                <p>Команда "AudioFree" быстро соберет и доставит Вашу посылку - от 1 до 2 дней по всей Росcии в зависимости от адреса</p>
            </div>
        </div>
        <div class="block-3">
            <div class="delivery__cards__card">
                <div class="delivery__cards__card__image">
                    <img src="../assets/image/delivery/money 1.svg" />
                </div>
                <div class="delivery__cards__card__title">
                    <p>Предоплата 0 руб.</p>
                </div>
                <div class="delivery__cards__card__text">
                    <p>Никаких предоплат при доставке по Москве и Санкт-Петербургу - платите при получении, когда удостоверитесь в качестве покупки</p>
                </div>
            </div>
        </div>
        <div class="block-2">
            <div class="delivery__cards__card">
                <div class="delivery__cards__card__image">
                    <img src="../assets/image/delivery/shopping 1.svg" />
                </div>
                <div class="delivery__cards__card__title">
                    <p>0 рисков при покупке</p>
                </div>
                <div class="delivery__cards__card__text">
                    <p>При покупке в "Audio Free" Вы обязательно получите чек и гарантийный талон. Мы всегда соблюдаем все права потребителей</p>
                </div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>

import BlockDeliveryTitleSubtitle from "@/components/blocks/BlockDeliveryTitleSubtitle"

export default {
    components:{
        BlockDeliveryTitleSubtitle
    }
}
</script>

<style lang="scss" scoped>
    .delivery{
        display: flex;
        flex-direction: column;
        background: #FFFFFF;
        height: 707px;
        &__title{
            display: flex;
            margin: -10px 0px 0px 475px;
        }
        &__subtitle{
            margin: -5px 0px 0px 443px;
            width: 1055px;
            height: 69px;
            font-family: Roboto;
            font-style: normal;
            font-weight: 400;
            font-size: 18px;
            line-height: 21px;
            text-align: center;
            color: #434343;
        }
        &__cards{
            display: flex;
            justify-content: space-between;
            margin-top: 32px;
            &__card{
                display: flex;
                flex-direction: column;
                align-items: center;
                width: 302px;
                height: 321px;
                background: #FFFFFF;
                box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.05);
                border-radius: 9px;
                &__image{
                    display: flex;
                    justify-content: center;
                    width: 89px;
                    height: 89px;
                    background: #F3F3F3;
                    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.05);
                    border-radius: 50%;
                    margin: 35px 0px 0px 0px;
                    img{
                        display: flex;
                    }
                }
                &__title{
                    display: flex;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    text-align: center;
                    color: #525252;
                    margin: 34px 0px 0px 3px;
                }
                &__text{
                    display: flex;
                    width: 246px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 14px;
                    line-height: 21px;
                    text-align: center;
                    color: #525252;
                    margin: 22px 0px 0px 10px;
                }
            }
        }
    }
@media (max-width: 1500px) {
    .delivery{
        display: flex;
        flex-direction: column;
        background: #FFFFFF;
        height: 707px;
        &__title{
            display: flex;
            margin: -10px 0px 0px 275px;
        }
        &__subtitle{
            margin: -5px 0px 0px 245px;
            width: 1050px;
            height: 69px;
            font-family: Roboto;
            font-style: normal;
            font-weight: normal;
            font-size: 18px;
            line-height: 21px;
            text-align: center;
            color: #434343;
        }
    }    
}
@media (max-width: 1280px) {
    .delivery{
        display: flex;
        flex-direction: column;
        background: #FFFFFF;
        height: 707px;
        &__title{
            display: flex;
            margin: -10px 0px 0px 175px;
        }
        &__subtitle{
            margin: -5px 0px 0px 145px;
            width: 1050px;
            height: 69px;
            font-family: Roboto;
            font-style: normal;
            font-weight: normal;
            font-size: 18px;
            line-height: 21px;
            text-align: center;
            color: #434343;
        }
    }    
}
@media (max-width: 1204px) {
    .delivery{
        display: flex;
        flex-direction: column;
        background: #FFFFFF;
        height: 707px;
        &__title{
            display: flex;
            margin: -10px 0px 0px 48px;
        }
        &__subtitle{
            margin: -5px 0px 0px 29px;
            width: 900px;
            height: 69px;
            font-family: Roboto;
            font-style: normal;
            font-weight: normal;
            font-size: 18px;
            line-height: 21px;
            text-align: center;
            color: #434343;
        }
    }    
}
@media (max-width: 768px) {
    .delivery{
        display: flex;
        flex-direction: column;
        background: #FFFFFF;
        height: 974px;
        &__title{
            display: flex;
            margin: -10px 0px 0px 48px;
        }
        &__subtitle{
            margin: -5px 0px 0px 80px;
            width: 600px;
            height: 69px;
            font-family: Roboto;
            font-style: normal;
            font-weight: normal;
            font-size: 18px;
            line-height: 21px;
            text-align: center;
            color: #434343;
        }
        &__cards{
            display: flex;
            flex-flow: column wrap;
            height: 700px;
            margin-top: 32px;
            &__card{
                display: flex;
                flex-direction: column;
                align-items: center;
                width: 302px;
                height: 321px;
                background: #FFFFFF;
                box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.05);
                border-radius: 9px;
                &__image{
                    display: flex;
                    justify-content: center;
                    width: 89px;
                    height: 89px;
                    background: #F3F3F3;
                    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.05);
                    border-radius: 50%;
                    margin: 35px 0px 0px 0px;
                    img{
                        display: flex;
                    }
                }
                &__title{
                    display: flex;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    text-align: center;
                    color: #525252;
                    margin: 34px 0px 0px 3px;
                }
                &__text{
                    display: flex;
                    width: 246px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 14px;
                    line-height: 21px;
                    text-align: center;
                    color: #525252;
                    margin: 22px 0px 0px 10px;
                }
            }
        }
    }    
}
@media (max-width: 414px) {
    .delivery{
        display: flex;
        flex-direction: column;
        background: #FFFFFF;
        height: 974px;
        &__title{
            display: flex;
            margin: -10px 0px 0px 10px;
        }
        &__subtitle{
            margin: -5px 0px 0px 10px;
            width: 400px;
            height: 69px;
            font-family: Roboto;
            font-style: normal;
            font-weight: normal;
            font-size: 17px;
            line-height: 21px;
            text-align: center;
            color: #434343;
        }
        &__cards{
            display: flex;
            flex-flow: column wrap;
            height: 700px;
            margin-top: 32px;
            &__card{
                display: flex;
                flex-direction: column;
                align-items: center;
                width: 178px;
                height: 319px;
                background: #FFFFFF;
                box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.05);
                border-radius: 9px;
                &__image{
                    display: flex;
                    justify-content: center;
                    width: 89px;
                    height: 89px;
                    background: #F3F3F3;
                    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.05);
                    border-radius: 50%;
                    margin: 35px 0px 0px 0px;
                    img{
                        display: flex;
                    }
                }
                &__title{
                    display: flex;
                    width: 115px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    text-align: center;
                    color: #525252;
                    margin: 34px 0px 0px 3px;
                }
                &__text{
                    display: flex;
                    width: 156px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 11px;
                    line-height: 21px;
                    text-align: center;
                    color: #525252;
                    margin: 22px 0px 0px 10px;
                }
            }
        }
    }
    .block-3{
        display: flex;
        .delivery__cards__card{
            display: flex;
            margin: 0px 0px 0px 80px;
            width: 250px;
            .delivery__cards__card__text{
                width: 246px;
            }
        }
    }
    .block-2{
        display: flex;
        .delivery__cards__card{
            display: flex;
            margin: 0px 0px 0px -130px;
        }
    }
}
@media (max-width: 375px) {
    .delivery{
        display: flex;
        flex-direction: column;
        background: #FFFFFF;
        height: 974px;
        &__title{
            display: flex;
            margin: 20px 0px 0px 0px;
        }
        &__subtitle{
            margin: -12px 0px 0px 8px;
            width: 359px;
            height: 70px;
            font-family: Roboto;
            font-style: normal;
            font-weight: 300;
            font-size: 16px;
            line-height: 19px;
            text-align: center;
            color: #434343;
        }
        &__cards{
            display: flex;
            flex-flow: column wrap;
            height: 700px;
            margin: 44px 0px 0px 5px;
            &__card{
                display: flex;
                flex-direction: column;
                align-items: center;
                width: 178px;
                height: 319px;
                background: #FFFFFF;
                box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.05);
                border-radius: 9px;
                &__image{
                    display: flex;
                    justify-content: center;
                    width: 89px;
                    height: 89px;
                    background: #F3F3F3;
                    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.05);
                    border-radius: 50%;
                    margin: 35px 0px 0px 3px;
                    img{
                        display: flex;
                    }
                }
                &__title{
                    display: flex;
                    width: 100px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 700;
                    font-size: 18px;
                    line-height: 21px;
                    text-align: center;
                    color: #525252;
                    margin: 25px 0px 0px 0px;
                }
                &__text{
                    display: flex;
                    width: 160px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 11px;
                    line-height: 20px;
                    text-align: center;
                    color: #525252;
                    margin: 22px 0px 0px -3px;
                }
            }
        }
    }
    .block-3{
        display: flex;
        .delivery__cards__card{
            display: flex;
            margin: 0px 0px 32px 56px;
            width: 250px;
            .delivery__cards__card__image{
                margin: 36px 0px 0px 2px;
            }
            .delivery__cards__card__title{
                margin: 20px 0px 0px 0px;
            }
            .delivery__cards__card__text{
                width: 240px;
                text-align: center;
                margin: 23px 14px 0px 0px;
            }
        }
    }
    .block-2{
        display: flex;
        margin: 0px 0px 0px 25px;
        .delivery__cards__card__image{
            margin: 36px 31px 0px 0px;
        }
        .delivery__cards__card__title{
            margin: 24px 30px 0px 0px;
            width: 160px;
        }
        .delivery__cards__card__text{
            margin: 23px 42px 0px 0px;
            width: 150px;
        }
        .delivery__cards__card{
            display: flex;
            margin: 0px 0px 0px -130px;
        }
    }
}
</style>