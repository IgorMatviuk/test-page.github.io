<template>
  <div class="card">
      <div class="card__container">
          <div class="card__container__sale-image">
              <div class="plus"></div>
              <div class="card__container__sale-image">
                <div class="card__container__sale-image__image">
                    <img src="@/components/blocks/ProductSale/besprovodnye-naushniki-baseus-d01-encok-wireless-headphone-ngd01-09-krasnyy-1-600x600-600x600 1.png" />
                </div>
                <div class="card__container__sale-image__sale">
                  <p>{{ content.sale }}</p>
              </div>
            </div>
          </div>
            <div class="card__container__star">
                <img src="@/components/blocks/BlockProductOneClick/star-active.svg"/>
                <img src="@/components/blocks/BlockProductOneClick/star-active.svg"/>
                <img src="@/components/blocks/BlockProductOneClick/star-active.svg"/>
                <img src="@/components/blocks/BlockProductOneClick/star-active.svg"/>
                <img src="@/components/blocks/BlockProductOneClick/star.svg"/>                
            </div>
            <div class="card__container__title">
                {{ content.title }}
            </div>
            <div class="title-mob">
                {{ content.titleMob }}
            </div>
            <div class="card__container__description">
                {{ content.description }}
            </div>
            <div class="card__container__pay-price">
                <div class="card__container__pay-price__pay"><button>Купить</button></div>
                <div class="card__container__pay-price__price">{{ content.price }}</div>
            </div>
      </div>
  </div>
</template>

<script>
export default {
    props: {
        content: {
          type: Object,
          required: true
        }
    }
}
</script>

<style lang="scss" scoped>
    .card{
        margin: 0px 0px 0px 30px;
        display: flex;
        width: 270px;
        height: 441px;
        background: #FFFFFF;
        box-shadow: 0px 0px 18px rgba(0, 0, 0, 0.1);
        border-radius: 9.5px;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 10px 15px 0px 15px;
            &__sale-image{
                display: flex;
                margin: 8px 0px 0px 15px;
                &__sale{
                    display: flex;
                    width: 46px;
                    height: 46px;
                    background: #97D513;
                    border-radius: 70px;
                    align-items: center;
                    margin: -14px 0px 0px -13px;
                    p{
                        display: flex;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: bold;
                        font-size: 13px;
                        line-height: 15px;
                        text-align: center;
                        color: #FFFFFF;
                        margin: 0px 0px 0px 10px;
                    }
                }
                &__image{
                    display: flex;
                }
            }
            &__star{
                display: flex;
                margin: -1px 0px 0px 73px;
                img{
                    margin: 0px 0px 0px 3px;
                }
            }
            &__title{
                display: flex;
                margin: 21px 0px 0px 1px;
                font-family: Roboto;
                font-style: normal;
                font-weight: 800;
                font-size: 14px;
                line-height: 20px;
                color: #353535;
            }
            &__description{
                display: flex;
                margin: 17px 0px 0px 2px;  
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 12px;
                line-height: 14px;
                color: #4B4B4B;              
            }
            &__pay-price{
                display: flex;
                justify-content: space-between;
                margin: 20px 0px 0px 0px;
                &__pay{
                    display: flex;
                    button{
                        width: 124px;
                        height: 38px;
                        background: linear-gradient(180deg, rgba(255, 255, 255, 0) 0%, rgba(0, 0, 0, 0.13) 98.96%), #8B75C8;
                        border-radius: 220px;
                        border: none;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: bold;
                        font-size: 13px;
                        line-height: 15px;
                        text-align: center;
                        color: #FFFFFF;
                    }
                }
                &__price{
                    display: flex;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: bold;
                    font-size: 26px;
                    line-height: 30px;
                    color: #444444;
                    margin: 2px 2px 0px 0px;
                }
            }
        }
    }
    .title-mob{
        display: none;
    }
    .plus{
        display: none;
    }
@media (max-width: 414px) {
    .card{
        margin: 0px 0px 0px 20px;
        display: flex;
        width: 174px;
        height: 222px;
        background: #FFFFFF;
        box-shadow: 0px 0px 18px rgba(0, 0, 0, 0.1);
        border-radius: 9.5px;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 10px 0px 0px 0px;
            &__sale-image{
                display: flex;
                flex-direction: row-reverse;
                margin: 8px 0px 0px 0px;
                &__sale{
                    display: flex;
                    z-index: 2;
                    width: 25px;
                    height: 25px;
                    background: #97D513;
                    border-radius: 70px;
                    align-items: center;
                    margin: -20px 0px 0px 5px;
                    p{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: bold;
                        font-size: 8.45px;
                        line-height: 10px;
                        display: flex;
                        align-items: center;
                        text-align: center;
                        color: #FFFFFF;
                        margin: 0px 0px 0px 5px;
                        z-index: 2;
                    }
                }
                &__image{
                    display: flex;
                    width: 115px;
                    height: 131px;
                    background: white;
                    margin: 0px 0px 0px 0px;
                    z-index: 1;
                    img{
                        display: none;
                    }
                }
            }
            &__star{
                display: flex;
                margin: 40px 0px 0px 0px;
                img{
                    margin-left: 4px;
                    width: 10px;
                }
            }
            &__title{
                display: none;
                margin: 21px 0px 0px 1px;
                font-family: Roboto;
                font-style: normal;
                font-weight: 800;
                font-size: 14px;
                line-height: 20px;
                color: #353535;
            }
            &__description{
                display: none;
                margin: 17px 0px 0px 2px;  
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 12px;
                line-height: 14px;
                color: #4B4B4B;              
            }
            &__pay-price{
                display: flex;
                justify-content: space-between;
                margin: 20px 0px 0px 0px;
                &__pay{
                    display: none;
                    button{
                        width: 124px;
                        height: 38px;
                        background: linear-gradient(180deg, rgba(255, 255, 255, 0) 0%, rgba(0, 0, 0, 0.13) 98.96%), #8B75C8;
                        border-radius: 220px;
                        border: none;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: bold;
                        font-size: 13px;
                        line-height: 15px;
                        text-align: center;
                        color: #FFFFFF;
                    }
                }
                &__price{
                    display: flex;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 700;
                    font-size: 18px;
                    line-height: 21px;
                    color: #8B75C8;
                    letter-spacing: -1px;
                    margin: -20px 0px 0px 100px;
                }
            }
        }
    }
    .title-mob{
        display: flex;
        margin: -45px 0px 0px 10px;
        width: 150px;
        font-family: Roboto;
        font-style: normal;
        font-weight: 700;
        font-size: 14px;
        line-height: 16px;
        color: #353535;
    }
    .plus{
        display: flex;
        z-index: 2;
        width: 25px;
        height: 25px;
        background: #EEEEEE;
        border-radius: 22px;
        margin: 0px 0px 0px 10px;
        background-image: url("../blocks/ProductBrand/plus.svg");
        background-repeat: no-repeat;
        background-position: 50% 50%;
        margin: -12px 0px 0px 0px;
        img{
            display: none;
            margin: 0px 0px 0px 5px;
        }
    }       
}
@media (max-width: 375px) {
    .card{
        margin: 0px 0px 0px 7px;
        display: flex;
        width: 174px;
        height: 222px;
        background: #FFFFFF;
        box-shadow: 0px 0px 18px rgba(0, 0, 0, 0.1);
        border-radius: 9.5px;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 10px 0px 0px 0px;
            &__sale-image{
                display: flex;
                flex-direction: row-reverse;
                margin: 8px 0px 0px 0px;
                &__sale{
                    display: flex;
                    z-index: 2;
                    width: 25px;
                    height: 25px;
                    background: #97D513;
                    border-radius: 70px;
                    align-items: center;
                    margin: -20px 0px 0px 5px;
                    p{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: bold;
                        font-size: 8.45px;
                        line-height: 10px;
                        display: flex;
                        align-items: center;
                        text-align: center;
                        color: #FFFFFF;
                        margin: 0px 0px 0px 5px;
                        z-index: 2;
                    }
                }
                &__image{
                    display: flex;
                    width: 108px;
                    height: 105px;
                    background: white;
                    margin: 0px 0px 0px 0px;
                    z-index: 1;
                    img{
                        display: none;
                    }
                }
            }
            &__star{
                display: flex;
                margin: 57px 0px 0px 5px;
                img{
                    margin-left: 4px;
                    width: 10px;
                }
            }
            &__title{
                display: none;
                margin: 21px 0px 0px 1px;
                font-family: Roboto;
                font-style: normal;
                font-weight: 800;
                font-size: 14px;
                line-height: 20px;
                color: #353535;
            }
            &__description{
                display: none;
                margin: 17px 0px 0px 2px;  
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 12px;
                line-height: 14px;
                color: #4B4B4B;              
            }
            &__pay-price{
                display: flex;
                justify-content: space-between;
                margin: 20px 0px 0px 0px;
                &__pay{
                    display: none;
                    button{
                        width: 124px;
                        height: 38px;
                        background: linear-gradient(180deg, rgba(255, 255, 255, 0) 0%, rgba(0, 0, 0, 0.13) 98.96%), #8B75C8;
                        border-radius: 220px;
                        border: none;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: bold;
                        font-size: 13px;
                        line-height: 15px;
                        text-align: center;
                        color: #FFFFFF;
                    }
                }
                &__price{
                    display: flex;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 700;
                    font-size: 18px;
                    line-height: 21px;
                    color: #8B75C8;
                    letter-spacing: -1px;
                    margin: -17px 0px 0px 100px;
                }
            }
        }
    }
    .title-mob{
        display: flex;
        margin: -52px 0px 0px 9px;
        width: 150px;
        font-family: Roboto;
        font-style: normal;
        font-weight: 700;
        font-size: 14px;
        line-height: 16px;
        color: #353535;
    }
    .plus{
        display: flex;
        z-index: 2;
        width: 25px;
        height: 25px;
        background: #EEEEEE;
        border-radius: 22px;
        margin: 0px 0px 0px 10px;
        background-image: url("../blocks/ProductBrand/plus.svg");
        background-repeat: no-repeat;
        background-position: 50% 50%;
        margin: -12px 0px 0px 0px;
        img{
            display: none;
            margin: 0px 0px 0px 5px;
        }
    }       
}
</style>