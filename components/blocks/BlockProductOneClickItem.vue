<template>
  <div class="card">
    <div class="card__container">
        <div class="card__container__header">
            <div class="card__container__header__state display-none">
                <div><img src="@/components/blocks/BlockProductOneClick/green.svg" /></div>
                <div><p>{{ content.state }}</p></div>
              </div>
            <div class="card__container__header__like-libra">
                <div class="card__container__header__like-libra__but">
                    <img src="@/components/blocks/BlockProductOneClick/libra.svg" />
                </div>
                <div class="card__container__header__like-libra__but display-none">
                    <img src="@/components/blocks/BlockProductOneClick/like.svg" />
                </div>
            </div>
      </div>
      <div class="card__container__header__image">
        <div class="image-mob" ></div>
        <img class="display-none" src="@/components/blocks/BlockProductOneClick/headphones1.png"/>
      </div>
      <div class="card__container__header__title-price">
          <div class="card__container__header__title-price__title">
              {{ content.title }}
          </div>
            <div class="title-mob">
              {{ content.titleMob }}
          </div>
          <div class="card__container__header__title-price__price-block">
              <div class="card__container__header__title-price__price-block__star">
                <img src="@/components/blocks/BlockProductOneClick/star-active.svg"/>
                <img src="@/components/blocks/BlockProductOneClick/star-active.svg"/>
                <img src="@/components/blocks/BlockProductOneClick/star-active.svg"/>
                <img src="@/components/blocks/BlockProductOneClick/star-active.svg"/>
                <img src="@/components/blocks/BlockProductOneClick/star.svg"/>
              </div>
              <div class="card__container__header__title-price__price-block__price">
                  <p>{{ content.price }}</p>
              </div>
          </div>
      </div>
      <div class="card__container__header__buy-basket">
        <div class="card__container__header__buy-basket__buy">
            <button><p>Купить в 1 клик</p></button>
            </div>
        <div class="card__container__header__buy-basket__basket">
            <button><p>В корзину</p></button>
            </div>
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
        height: 450px;
        background: #FFFFFF;
        box-shadow: 0px 5px 18px rgba(0, 0, 0, 0.1);
        border-radius: 9.5px;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 10px 15px 0px 15px;
            &__header{
                display: flex;
                align-items: center;
                width: 100%;
                &__state{
                    display: flex;
                    align-items: center;
                    width: 104px;
                    height: 23px;
                    border: 1px solid #DCDCDC;
                    box-sizing: border-box;
                    border-radius: 14px;
                    margin: 0px 0px 0px -1px;
                    p{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: normal;
                        font-size: 12px;
                        line-height: 14px;
                        display: flex;
                        align-items: center;
                        text-align: center;
                        color: #454545;
                        margin: 0px 0px 0px 10px;
                    }
                    img{
                        margin: 0px 0px 0px 2px;
                    }
                }
                &__like-libra{
                    display: flex;
                    margin: 0px 0px 0px 55px;
                    &__but{
                        display: flex;
                        width: 33px;
                        height: 33px;
                        background: #EEEEEE;
                        border-radius: 22px;
                        margin: 0px 0px 0px 10px;
                        img{
                            display: flex;
                            margin: 0px 0px 0px 5px;
                        }
                    }
                    &__but:hover{
                        background: #0DB10A;
                    }
                }
                &__image{
                    margin: 0px 0px 0px 0px;
                }
                &__title-price{
                    display: flex;
                    flex-direction: column;
                    margin: 34px 0px 0px -1px;
                    &__title{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: 500;
                        font-size: 14px;
                        line-height: 20px;
                        color: #353535;
                        font-weight: 700;
                    }
                    &__price-block{
                        display: flex;
                        margin: 12px 0px 0px 0px;
                        &__star{
                            display: flex;
                            margin: 1px 0px 0px -6px;
                            img{
                                margin-left: 3px;
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
                            margin: 0px 0px 0px 66px;
                        }
                    }
                }
                &__buy-basket{
                    display: flex;
                    flex-direction: row;
                    &__buy{
                        display: flex;
                        margin: 25px 0px 0px -3px;
                        button{
                            width: 131px;
                            height: 39px;
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
                    &__basket{
                        display: flex;
                        margin: 25px 0px 0px 13px;
                        button{
                            width: 103px;
                            height: 39px;
                            border: 1px solid #A9A9A9;
                            box-sizing: border-box;
                            border-radius: 220px;
                            font-family: Roboto;
                            font-style: normal;
                            font-weight: normal;
                            font-size: 14px;
                            line-height: 16px;
                            display: flex;
                            align-items: center;
                            text-align: center;
                            color: #393939;
                            p{
                                margin: 0px 0px 0px 10px;
                            }
                        }
                    }
                }
            }
        }
    }
    .title-mob{
        display: none;
    }
@media (max-width: 375px) {
    .card{
        margin: 0px 0px 0px 10px;
        display: flex;
        width: 174px;
        height: 222px;
        background: #FFFFFF;
        box-shadow: 0px 5px 18px rgba(0, 0, 0, 0.1);
        border-radius: 9px;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 10px 15px 0px 15px;
            &__header{
                display: flex;
                align-items: center;
                width: 100%;
                &__state{
                    display: flex;
                    align-items: center;
                    width: 104px;
                    height: 23px;
                    border: 1px solid #DCDCDC;
                    box-sizing: border-box;
                    border-radius: 14px;
                    margin: 0px 0px 0px -1px;
                    p{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: normal;
                        font-size: 12px;
                        line-height: 14px;
                        display: flex;
                        align-items: center;
                        text-align: center;
                        color: #454545;
                        margin: 0px 0px 0px 10px;
                    }
                    img{
                        margin: 0px 0px 0px 2px;
                    }
                }
                &__like-libra{
                    display: flex;
                    margin: 0px 0px 0px 116px;
                    
    
                    &__but{
                        display: flex;
                        width: 25px;
                        height: 25px;
                        background: #EEEEEE;
                        border-radius: 22px;
                        margin: 0px 0px 0px 10px;
                        background-image: url("../blocks/ProductBrand/plus.svg");
                        background-repeat: no-repeat;
                        background-position: 50% 50%;
                        img{
                            display: none;
                            margin: 0px 0px 0px 5px;
                        }
                    }
                    &__but:hover{
                        background: #0DB10A;
                    }
                }
                &__image{
                    margin: 0px 0px 0px 0px;
                }
                &__title-price{
                    display: flex;
                    flex-direction: column;
                    margin: 34px 0px 0px -1px;
                    &__title{
                        display: none;
                    }
                    &__price-block{
                        display: flex;
                        margin: 12px 0px 0px 0px;
                        &__star{
                            display: flex;
                            margin: -10px 0px 0px -7px;
                            img{
                                margin-left: 4px;
                                width: 10px;
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
                            margin: -10px 0px 0px 25px;
                        }
                    }
                }
                &__buy-basket{
                    display: flex;
                    flex-direction: row;
                    &__buy{
                        display: flex;
                        margin: 25px 0px 0px -3px;
                        button{
                            width: 131px;
                            height: 39px;
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
                    &__basket{
                        display: flex;
                        margin: 25px 0px 0px 13px;
                        button{
                            width: 103px;
                            height: 39px;
                            border: 1px solid #A9A9A9;
                            box-sizing: border-box;
                            border-radius: 220px;
                            font-family: Roboto;
                            font-style: normal;
                            font-weight: normal;
                            font-size: 14px;
                            line-height: 16px;
                            display: flex;
                            align-items: center;
                            text-align: center;
                            color: #393939;
                            p{
                                margin: 0px 0px 0px 10px;
                            }
                        }
                    }
                }
            }
        }
    }
    .display-none{
        display: none;
    } 
    .image-mob{
        display: flex;
        width: 120px;
        height: 131px;  
        margin: -20px 0px 0px 5px;
        background-image: url("../blocks/ProductBrand/besprovodnye.png");
        background-repeat: no-repeat;      
    } 
    .title-mob{
        display: flex;
        margin: -29px 0px 0px -1px;
        width: 150px;
        font-family: Roboto;
        font-style: normal;
        font-weight: 700;
        font-size: 14px;
        line-height: 16px;
        color: #353535;
    }       
}
</style>