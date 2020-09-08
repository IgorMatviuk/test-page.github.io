<template>
  <div>
    <div class="footer">
        <div class="footer__container">
            <div class="footer__container__cabinet">
                <div class="footer__container__cabinet__title">
                    <p>Личный кабинет</p>
                </div>
                <div class="footer__container__cabinet__menu">
                    <p>Зарегистрироваться</p>
                    <p>Войти в аккаунт</p>
                    <p>Отложенные товары</p>
                    <p>Ваши заказы</p>
                </div>
                <div class="footer__container__cabinet__text">
                    <p>Закажите обратный звонок:</p>
                </div>
                <div class="footer__container__cabinet__input">
                    <input type="text"  value="Ваш номер телефона"/>
                    <div class="footer__container__cabinet__input__box">
                        <img src="../assets/image/Footer/inp.svg" />
                    </div>
                </div>
            </div>
            <div></div>
            <div class="footer__container__categories">
                <div class="footer__container__categories__title">
                    <p>Категории</p>
                </div>
                <div class="footer__container__categories__menu">
                    <p>TRUE WIRELESS</p>
                    <p>Гарнитуры</p>
                    <p>Накладные</p>
                    <p>Полноразмерные</p>
                    <p>С проводом</p>
                    <p>С шейным ободком</p>
                </div>
            </div>
            <div class="footer__container__store">
                <div class="footer__container__store__title">
                    <p>Магазин</p>
                </div>
                <div class="footer__container__store__menu">
                    <p>О компании</p>
                    <p>Доставка и оплата</p>
                    <p>Гарантия и возврат</p> 
                    <p>Пункты самовывоза</p>
                    <p>Отзывы</p>
                    <p>Блог</p>
                    <p>Контакты</p>
                </div>
            </div>
            <div class="contacts-line-mob desktop-none"></div>
            <div class="footer__container__contacts">
                <div class="footer__container__contacts__title">
                    <p>Контакты</p>
                </div>
                <div class="footer__container__contacts__bloks">
                    <div class="footer__container__contacts__bloks__block-phone">
                        <div class="footer__container__contacts__bloks__block-phone__button">
                            <img src="../assets/image/Footer/phone.svg" />
                        </div>
                        <div class="footer__container__contacts__bloks__block-phone__text">
                            <p>Бесплатный звонок по РФ</p>
                            <p><a>8 800 551-92-02</a></p>
                        </div>
                    </div>
                    <div class="footer__container__contacts__bloks__block-address">
                        <div class="footer__container__contacts__bloks__block-address__button">
                            <img src="../assets/image/Footer/localC.svg" />
                        </div>
                        <div class="footer__container__contacts__bloks__block-address__text">
                            <p>Санкт-Петербург,</p>
                            <p><a>Дачный пр. 21</a></p>
                        </div>
                    </div>
                    <div class="footer__container__contacts__bloks__block-mail">
                        <div class="footer__container__contacts__bloks__block-mail__button">
                            <img src="../assets/image/Footer/mailC.svg" />
                        </div>
                        <div class="footer__container__contacts__bloks__block-mail__text">
                            <p>По всем вопросам пишите:</p>
                            <p><a>hello@audiofree.ru</a></p>
                        </div>
                    </div>
                </div>
                <div class="footer__container__social">
                    <div class="footer__container__social__icon">
                        <img src="../assets/image/Footer/vk.svg" />
                    </div>
                    <div class="footer__container__social__icon">
                        <img src="../assets/image/Footer/fb.svg" />
                    </div>
                    <div class="footer__container__social__icon">
                        <img src="../assets/image/Footer/tg.svg" />
                    </div>
                    <div class="footer__container__social__icon">
                        <img src="../assets/image/Footer/wa.svg" />
                    </div>
                    <div class="footer__container__social__icon">
                        <img src="../assets/image/Footer/vi.svg" />
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="sub-footer">
        <div class="sub-footer-line-one desktop-none"></div>
        <div class="sub-footer__container">
            <div class="sub-footer__container__left">
                <p>© 2019 audiofree.ru Все права защищены</p>
            </div>
            <div class="sub-footer-line-two desktop-none"></div>
            <div class="sub-footer__container__center">
                <img src="../assets/image/Footer/logo.svg" />
                <p>AudioFree</p>
            </div>
            <div class="sub-footer__container__right">
                <p>Политика конфиденциальности</p>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .footer{
        height: 383px;
        background: #251C41;
        &__container{
            display: flex;
            justify-content: space-between;
            padding: 70px 370px 0px 370px;
            &__cabinet{
                display: flex;
                flex-direction: column;
                margin: 0px 0px 0px 2px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__menu{
                    display: flex;
                    flex-direction: column;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 24px;
                    color: #FFFFFF;
                    margin: 45px 0px 0px 0px;
                }
                &__text{
                    display: flex;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 12px;
                    line-height: 18px;
                    color: #FFFFFF;
                    margin: 40px 0px 0px 0px;
                }
                &__input{
                    display: flex;
                    margin: 5px 0px 0px -1px;
                    input[type="text"]{padding-left: 15px;}
                    input{
                        height: 40px;
                        width: 172px;
                        border: 0.813953px solid #C4C4C4;
                        box-sizing: border-box;
                        border-bottom-left-radius: 9px;
                        border-top-left-radius: 9px;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: normal;
                        font-size: 11.3953px;
                        line-height: 13px;
                        display: flex;
                        align-items: center;
                        color: #9B9B9B;
                        background-color: transparent;
                    }
                    &__box{
                        width: 38px;
                        height: 40px;
                        background: #97D513;
                        border: 0.813953px solid #C4C4C4;
                        box-sizing: border-box;
                        border-radius: 0px 9px 9px 0px;
                        display: flex;
                        justify-content: center;
                    }
                }
            }
            &__categories{
                display: flex;
                flex-direction: column;
                margin: 2px 70px 0px 0px;
                width: 190px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__menu{
                    display: flex;
                    flex-direction: column;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 24px;
                    color: #FFFFFF;
                    margin: 43px 0px 0px 0px;
                }
            }
            &__store{
                display: flex;
                flex-direction: column;
                margin: 1px 69px 0px 0px;
                width: 190px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__menu{
                    display: flex;
                    flex-direction: column;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 24px;
                    color: #FFFFFF;
                    margin: 45px 0px 0px 0px;
                }
            }
            &__contacts{
                display: flex;
                flex-direction: column;
                margin: 1px 0px 0px 0px;
                width: 256px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__bloks{
                    display: flex;
                    flex-direction: column;
                    margin: 42px 0px 0px -1px;
                    &__block-phone{
                        display: flex;
                        flex-direction: row;
                        &__button{
                            display: flex;
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            margin: 0px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 13px;
                                line-height: 15px;
                                color: #AEAEAE;
                                a{
                                    font-family: Roboto;
                                    font-style: normal;
                                    font-weight: bold;
                                    font-size: 24px;
                                    line-height: 28px;
                                    color: #FFFFFF;
                                }
                            }
                        }
                    }
                    &__block-address{
                        display: flex;
                        flex-direction: row;
                        margin: 13px 0px 0px 0px;
                        &__button{
                            display: flex;
                            height: 40px;
                            width: 40px;
                            background: #97D413;
                            border-radius: 50%;
                            justify-content: center;
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            margin: 2px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 14px;
                                line-height: 18px;
                                color: #FFFFFF;
                                a{
                                    font-weight: 600;
                                }
                            }
                        }
                    }
                    &__block-mail{
                        display: flex;
                        flex-direction: row;
                        margin: 15px 0px 0px 0px;
                        &__button{
                            display: flex;
                            height: 40px;
                            width: 40px;
                            background: #97D413;
                            border-radius: 50%;
                            justify-content: center;
                            img{
                                margin: 5px 0px 0px 0px;
                            }
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            margin: 0px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 14px;
                                line-height: 18px;
                                color: #FFFFFF;
                            a{
                                    font-weight: 600;
                                }
                            }
                        }
                    }
                }
            }
            &__social{
                display: flex;
                flex-direction: row;
                margin: 20px 0px 0px 42px;
                &__icon{
                    display: flex;
                    width: 26px;
                    height: 26px;
                    border-radius: 50%;
                    margin: 0px 0px 0px 9px;
                }
            }
        }
    }
    .sub-footer{
        height: 43px;
        background: #180E35;
        &__container{
            display: flex;
            justify-content: space-between;
            margin: 0px 370px 0px 370px;
            &__left{
                display: flex;
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 16px;
                text-align: right;
                color: #FFFFFF;
                margin: 12px 0px 0px 1px;
            }
            &__center{
                display: flex;
                flex-direction: row;
                align-items: center;
                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 18px;
                line-height: 21px;
                display: flex;
                align-items: center;
                color: #FFFFFF;
                margin: 5px 47px 0px 0px;
                img{
                    margin: 0px 5px 0px 0px;
                }
                p{
                    margin: 3px 0px 0px 0px;
                }
            }
            &__right    {
                display: flex;
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 16px;
                color: #FFFFFF;
                p{
                    margin: 11px -10px 0px 0px;
                }
            }
        }        
    }
    .desktop-none{
        display: none;
    }
@media (max-width: 1650px) {
    .footer{
        height: 383px;
        background: #251C41;
        &__container{
            display: flex;
            justify-content: space-between;
            padding: 70px 270px 0px 270px;
            &__contacts{
                display: flex;
                flex-direction: column;
                margin: 1px 0px 0px 0px;
                width: 256px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__bloks{
                    display: flex;
                    flex-direction: column;
                    margin: 42px 0px 0px -1px;
                    &__block-phone{
                        display: flex;
                        flex-direction: row;
                        &__button{
                            display: flex;
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            margin: 0px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 13px;
                                line-height: 15px;
                                color: #AEAEAE;
                                a{
                                    font-family: Roboto;
                                    font-style: normal;
                                    font-weight: bold;
                                    font-size: 24px;
                                    line-height: 28px;
                                    color: #FFFFFF;
                                }
                            }
                        }
                    }
                    &__block-address{
                        display: flex;
                        flex-direction: row;
                        margin: 13px 0px 0px 0px;
                        &__button{
                            display: flex;
                            height: 40px;
                            width: 40px;
                            background: #97D413;
                            border-radius: 50%;
                            justify-content: center;
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            margin: 2px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 14px;
                                line-height: 18px;
                                color: #FFFFFF;
                                a{
                                    font-weight: 600;
                                }
                            }
                        }
                    }
                    &__block-mail{
                        display: flex;
                        flex-direction: row;
                        margin: 15px 0px 0px 0px;
                        &__button{
                            display: flex;
                            height: 40px;
                            width: 40px;
                            background: #97D413;
                            border-radius: 50%;
                            justify-content: center;
                            img{
                                margin: 5px 0px 0px 0px;
                            }
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            margin: 0px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 14px;
                                line-height: 18px;
                                color: #FFFFFF;
                            a{
                                    font-weight: 600;
                                }
                            }
                        }
                    }
                }
            }
            &__social{
                display: flex;
                flex-direction: row;
                margin: 10px 0px 0px 42px;
                &__icon{
                    display: flex;
                    width: 26px;
                    height: 26px;
                    border-radius: 50%;
                    margin: 0px 0px 0px 9px;
                }
            }
        }
    }
    .desktop-none{
        display: none;
    }
}
@media (max-width: 1410px) {
    .footer{
        height: 383px;
        background: #251C41;
        &__container{
            display: flex;
            justify-content: space-between;
            padding: 70px 70px 0px 70px;
            &__contacts{
                display: flex;
                flex-direction: column;
                margin: 1px 0px 0px 0px;
                width: 256px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__bloks{
                    display: flex;
                    flex-direction: column;
                    margin: 42px 0px 0px -1px;
                    &__block-phone{
                        display: flex;
                        flex-direction: row;
                        &__button{
                            display: flex;
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            margin: 0px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 13px;
                                line-height: 15px;
                                color: #AEAEAE;
                                a{
                                    font-family: Roboto;
                                    font-style: normal;
                                    font-weight: bold;
                                    font-size: 24px;
                                    line-height: 28px;
                                    color: #FFFFFF;
                                }
                            }
                        }
                    }
                    &__block-address{
                        display: flex;
                        flex-direction: row;
                        margin: 13px 0px 0px 0px;
                        &__button{
                            display: flex;
                            height: 40px;
                            width: 40px;
                            background: #97D413;
                            border-radius: 50%;
                            justify-content: center;
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            margin: 2px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 14px;
                                line-height: 18px;
                                color: #FFFFFF;
                                a{
                                    font-weight: 600;
                                }
                            }
                        }
                    }
                    &__block-mail{
                        display: flex;
                        flex-direction: row;
                        margin: 15px 0px 0px 0px;
                        &__button{
                            display: flex;
                            height: 40px;
                            width: 40px;
                            background: #97D413;
                            border-radius: 50%;
                            justify-content: center;
                            img{
                                margin: 5px 0px 0px 0px;
                            }
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            margin: 0px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 14px;
                                line-height: 18px;
                                color: #FFFFFF;
                            a{
                                    font-weight: 600;
                                }
                            }
                        }
                    }
                }
            }
            &__social{
                display: flex;
                flex-direction: row;
                margin: 10px 0px 0px 42px;
                &__icon{
                    display: flex;
                    width: 26px;
                    height: 26px;
                    border-radius: 50%;
                    margin: 0px 0px 0px 9px;
                }
            }
        }
    }
    .sub-footer{
        height: 43px;
        background: #180E35;
        &__container{
            display: flex;
            justify-content: space-between;
            margin: 0px 70px 0px 70px;
            &__left{
                display: flex;
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 16px;
                text-align: right;
                color: #FFFFFF;
                margin: 12px 0px 0px 1px;
            }
            &__center{
                display: flex;
                flex-direction: row;
                align-items: center;
                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 18px;
                line-height: 21px;
                display: flex;
                align-items: center;
                color: #FFFFFF;
                margin: 5px 47px 0px 0px;
                img{
                    margin: 0px 5px 0px 0px;
                }
                p{
                    margin: 3px 0px 0px 0px;
                }
            }
            &__right    {
                display: flex;
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 16px;
                color: #FFFFFF;
                p{
                    margin: 11px -10px 0px 0px;
                }
            }
        }        
    } 
    .desktop-none{
        display: none;
    }   
}
@media (max-width: 960px) {
    .footer{
        height: 383px;
        background: #251C41;
        &__container{
            display: flex;
            justify-content: space-between;
            padding: 70px 70px 0px 70px;
            &__cabinet{
                display: none;
                flex-direction: column;
                margin: 0px 0px 0px 2px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__menu{
                    display: flex;
                    flex-direction: column;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 24px;
                    color: #FFFFFF;
                    margin: 45px 0px 0px 0px;
                }
                &__text{
                    display: flex;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 12px;
                    line-height: 18px;
                    color: #FFFFFF;
                    margin: 40px 0px 0px 0px;
                }
                &__input{
                    display: flex;
                    margin: 5px 0px 0px -1px;
                    input[type="text"]{padding-left: 15px;}
                    input{
                        height: 40px;
                        width: 172px;
                        border: 0.813953px solid #C4C4C4;
                        box-sizing: border-box;
                        border-bottom-left-radius: 9px;
                        border-top-left-radius: 9px;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: normal;
                        font-size: 11.3953px;
                        line-height: 13px;
                        display: flex;
                        align-items: center;
                        color: #9B9B9B;
                        background-color: transparent;
                    }
                    &__box{
                        width: 38px;
                        height: 40px;
                        background: #97D513;
                        border: 0.813953px solid #C4C4C4;
                        box-sizing: border-box;
                        border-radius: 0px 9px 9px 0px;
                        display: flex;
                        justify-content: center;
                    }
                }
            }
            &__categories{
                display: flex;
                flex-direction: column;
                margin: 2px 70px 0px 0px;
                width: 190px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__menu{
                    display: flex;
                    flex-direction: column;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 24px;
                    color: #FFFFFF;
                    margin: 43px 0px 0px 0px;
                }
            }
            &__store{
                display: flex;
                flex-direction: column;
                margin: 1px 69px 0px 0px;
                width: 190px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__menu{
                    display: flex;
                    flex-direction: column;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 24px;
                    color: #FFFFFF;
                    margin: 45px 0px 0px 0px;
                }
            }
            &__contacts{
                display: flex;
                flex-direction: column;
                margin: 1px 0px 0px 0px;
                width: 256px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__bloks{
                    display: flex;
                    flex-direction: column;
                    margin: 42px 0px 0px -1px;
                    &__block-phone{
                        display: flex;
                        flex-direction: row;
                        &__button{
                            display: flex;
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            margin: 0px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 13px;
                                line-height: 15px;
                                color: #AEAEAE;
                                a{
                                    font-family: Roboto;
                                    font-style: normal;
                                    font-weight: bold;
                                    font-size: 24px;
                                    line-height: 28px;
                                    color: #FFFFFF;
                                }
                            }
                        }
                    }
                    &__block-address{
                        display: flex;
                        flex-direction: row;
                        margin: 13px 0px 0px 0px;
                        &__button{
                            display: flex;
                            height: 40px;
                            width: 40px;
                            background: #97D413;
                            border-radius: 50%;
                            justify-content: center;
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            margin: 2px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 14px;
                                line-height: 18px;
                                color: #FFFFFF;
                                a{
                                    font-weight: 600;
                                }
                            }
                        }
                    }
                    &__block-mail{
                        display: flex;
                        flex-direction: row;
                        margin: 15px 0px 0px 0px;
                        &__button{
                            display: flex;
                            height: 40px;
                            width: 40px;
                            background: #97D413;
                            border-radius: 50%;
                            justify-content: center;
                            img{
                                margin: 5px 0px 0px 0px;
                            }
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            margin: 0px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 14px;
                                line-height: 18px;
                                color: #FFFFFF;
                            a{
                                    font-weight: 600;
                                }
                            }
                        }
                    }
                }
            }
            &__social{
                display: flex;
                flex-direction: row;
                margin: 10px 0px 0px 42px;
                &__icon{
                    display: flex;
                    width: 26px;
                    height: 26px;
                    border-radius: 50%;
                    margin: 0px 0px 0px 9px;
                }
            }
        }
    }
    .sub-footer{
        height: 43px;
        background: #180E35;
        &__container{
            display: flex;
            justify-content: space-between;
            margin: 0px 70px 0px 70px;
            &__left{
                display: flex;
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 16px;
                text-align: right;
                color: #FFFFFF;
                margin: 12px 0px 0px 1px;
            }
            &__center{
                display: flex;
                flex-direction: row;
                align-items: center;
                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 18px;
                line-height: 21px;
                display: flex;
                align-items: center;
                color: #FFFFFF;
                margin: 5px 47px 0px 0px;
                img{
                    margin: 0px 5px 0px 0px;
                }
                p{
                    margin: 3px 0px 0px 0px;
                }
            }
            &__right    {
                display: flex;
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 16px;
                color: #FFFFFF;
                p{
                    margin: 11px -10px 0px 0px;
                }
            }
        }        
    }
    .desktop-none{
        display: none;
    }   
}
@media (max-width: 768px) {
    .footer{
        height: 383px;
        background: #251C41;
        &__container{
            display: flex;
            justify-content: space-evenly;
            padding: 70px 70px 0px 70px;
            &__cabinet{
                display: none;
                flex-direction: column;
                margin: 0px 0px 0px 2px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__menu{
                    display: flex;
                    flex-direction: column;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 24px;
                    color: #FFFFFF;
                    margin: 45px 0px 0px 0px;
                }
                &__text{
                    display: flex;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 12px;
                    line-height: 18px;
                    color: #FFFFFF;
                    margin: 40px 0px 0px 0px;
                }
                &__input{
                    display: flex;
                    margin: 5px 0px 0px -1px;
                    input[type="text"]{padding-left: 15px;}
                    input{
                        height: 40px;
                        width: 172px;
                        border: 0.813953px solid #C4C4C4;
                        box-sizing: border-box;
                        border-bottom-left-radius: 9px;
                        border-top-left-radius: 9px;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: normal;
                        font-size: 11.3953px;
                        line-height: 13px;
                        display: flex;
                        align-items: center;
                        color: #9B9B9B;
                        background-color: transparent;
                    }
                    &__box{
                        width: 38px;
                        height: 40px;
                        background: #97D513;
                        border: 0.813953px solid #C4C4C4;
                        box-sizing: border-box;
                        border-radius: 0px 9px 9px 0px;
                        display: flex;
                        justify-content: center;
                    }
                }
            }
            &__categories{
                display: none;
                flex-direction: column;
                margin: 2px 70px 0px 0px;
                width: 190px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__menu{
                    display: flex;
                    flex-direction: column;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 24px;
                    color: #FFFFFF;
                    margin: 43px 0px 0px 0px;
                }
            }
            &__store{
                display: flex;
                flex-direction: column;
                margin: 1px 69px 0px 0px;
                width: 190px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__menu{
                    display: flex;
                    flex-direction: column;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 24px;
                    color: #FFFFFF;
                    margin: 45px 0px 0px 0px;
                }
            }
            &__contacts{
                display: flex;
                flex-direction: column;
                margin: 1px 0px 0px 0px;
                width: 256px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__bloks{
                    display: flex;
                    flex-direction: column;
                    margin: 42px 0px 0px -1px;
                    &__block-phone{
                        display: flex;
                        flex-direction: row;
                        &__button{
                            display: flex;
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            margin: 0px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 13px;
                                line-height: 15px;
                                color: #AEAEAE;
                                a{
                                    font-family: Roboto;
                                    font-style: normal;
                                    font-weight: bold;
                                    font-size: 24px;
                                    line-height: 28px;
                                    color: #FFFFFF;
                                }
                            }
                        }
                    }
                    &__block-address{
                        display: flex;
                        flex-direction: row;
                        margin: 13px 0px 0px 0px;
                        &__button{
                            display: flex;
                            height: 40px;
                            width: 40px;
                            background: #97D413;
                            border-radius: 50%;
                            justify-content: center;
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            margin: 2px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 14px;
                                line-height: 18px;
                                color: #FFFFFF;
                                a{
                                    font-weight: 600;
                                }
                            }
                        }
                    }
                    &__block-mail{
                        display: flex;
                        flex-direction: row;
                        margin: 15px 0px 0px 0px;
                        &__button{
                            display: flex;
                            height: 40px;
                            width: 40px;
                            background: #97D413;
                            border-radius: 50%;
                            justify-content: center;
                            img{
                                margin: 5px 0px 0px 0px;
                            }
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            margin: 0px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 14px;
                                line-height: 18px;
                                color: #FFFFFF;
                            a{
                                    font-weight: 600;
                                }
                            }
                        }
                    }
                }
            }
            &__social{
                display: flex;
                flex-direction: row;
                margin: 10px 0px 0px 42px;
                &__icon{
                    display: flex;
                    width: 26px;
                    height: 26px;
                    border-radius: 50%;
                    margin: 0px 0px 0px 9px;
                }
            }
        }
    }
    .sub-footer{
        height: 43px;
        background: #180E35;
        &__container{
            display: flex;
            justify-content: space-evenly;
            margin: 0px 30px 0px 30px;
            &__left{
                display: flex;
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 16px;
                text-align: right;
                color: #FFFFFF;
                margin: 12px 0px 0px 1px;
            }
            &__center{
                display: flex;
                flex-direction: row;
                align-items: center;
                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 18px;
                line-height: 21px;
                display: flex;
                align-items: center;
                color: #FFFFFF;
                margin: 5px 47px 0px 0px;
                img{
                    margin: 0px 5px 0px 0px;
                }
                p{
                    margin: 3px 0px 0px 0px;
                }
            }
            &__right    {
                display: flex;
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 16px;
                color: #FFFFFF;
                p{
                    margin: 11px -10px 0px 0px;
                }
            }
        }        
    }
    .desktop-none{
        display: none;
    }    
}
@media (max-width: 414px) {
    .footer{
        height: 644px;
        background: #251C41;
        &__container{
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 70px 0px 0px 0px;
            &__cabinet{
                display: none;
                flex-direction: column;
                margin: 0px 0px 0px 2px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__menu{
                    display: flex;
                    flex-direction: column;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 24px;
                    color: #FFFFFF;
                    margin: 45px 0px 0px 0px;
                }
                &__text{
                    display: flex;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 12px;
                    line-height: 18px;
                    color: #FFFFFF;
                    margin: 40px 0px 0px 0px;
                }
                &__input{
                    display: flex;
                    margin: 5px 0px 0px -1px;
                    input[type="text"]{padding-left: 15px;}
                    input{
                        height: 40px;
                        width: 172px;
                        border: 0.813953px solid #C4C4C4;
                        box-sizing: border-box;
                        border-bottom-left-radius: 9px;
                        border-top-left-radius: 9px;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: normal;
                        font-size: 11.3953px;
                        line-height: 13px;
                        display: flex;
                        align-items: center;
                        color: #9B9B9B;
                        background-color: transparent;
                    }
                    &__box{
                        width: 38px;
                        height: 40px;
                        background: #97D513;
                        border: 0.813953px solid #C4C4C4;
                        box-sizing: border-box;
                        border-radius: 0px 9px 9px 0px;
                        display: flex;
                        justify-content: center;
                    }
                }
            }
            &__categories{
                display: none;
                flex-direction: column;
                margin: 2px 70px 0px 0px;
                width: 190px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__menu{
                    display: flex;
                    flex-direction: column;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 24px;
                    color: #FFFFFF;
                    margin: 43px 0px 0px 0px;
                }
            }
            &__store{
                display: flex;
                flex-direction: column;
                margin: 1px 0px 0px 0px;
                width: 190px;
                align-items: center;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                    align-items: center;
                }
                &__menu{
                    align-items: center;
                    display: flex;
                    flex-direction: column;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 24px;
                    color: #FFFFFF;
                    margin: 45px 0px 0px 0px;
                }
            }
            &__contacts{
                display: flex;
                flex-direction: column;
                align-items: center;
                margin: 40px 0px 0px 0px;
                width: 256px;
                &__title{
                    align-items: center;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__bloks{
                    display: flex;
                    flex-direction: column;
                    align-items: center;
                    margin: 42px 0px 0px -1px;
                    &__block-phone{
                        display: flex;
                        flex-direction: row;
                        &__button{
                            display: none;
                        }
                        &__text{
                            align-items: center;
                            display: flex;
                            flex-direction: column;
                            margin: 0px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 13px;
                                line-height: 15px;
                                color: #AEAEAE;
                                a{
                                    font-family: Roboto;
                                    font-style: normal;
                                    font-weight: bold;
                                    font-size: 24px;
                                    line-height: 28px;
                                    color: #FFFFFF;
                                }
                            }
                        }
                    }
                    &__block-address{
                        display: flex;
                        flex-direction: row;
                        margin: 13px 0px 0px 0px;
                        &__button{
                            display: none;
                            height: 40px;
                            width: 40px;
                            background: #97D413;
                            border-radius: 50%;
                            justify-content: center;
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            align-items: center;
                            margin: 2px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 14px;
                                line-height: 18px;
                                color: #FFFFFF;
                                a{
                                    font-weight: 600;
                                }
                            }
                        }
                    }
                    &__block-mail{
                        display: flex;
                        flex-direction: row;
                        margin: 15px 0px 0px 0px;
                        &__button{
                            display: none;
                            height: 40px;
                            width: 40px;
                            background: #97D413;
                            border-radius: 50%;
                            justify-content: center;
                            img{
                                margin: 5px 0px 0px 0px;
                            }
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            align-items: center;
                            margin: 0px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 14px;
                                line-height: 18px;
                                color: #FFFFFF;
                            a{
                                    font-weight: 600;
                                }
                            }
                        }
                    }
                }
            }
            &__social{
                display: flex;
                flex-direction: row;
                margin: 30px 0px 0px 0px;
                align-items: center;
                &__icon{
                    display: flex;
                    width: 26px;
                    height: 26px;
                    border-radius: 50%;
                    margin: 0px 0px 0px 9px;
                }
            }
        }
    }
    .sub-footer{
        height: 81px;
        background: #251C41;
        &__container{
            display: flex;
            flex-direction: column-reverse;
            align-items: center;
            margin: 0px 0px 0px 0px;
            &__left{
                display: flex;
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 16px;
                text-align: right;
                color: #FFFFFF;
                margin: 12px 0px 0px 1px;
            }
            &__center{
                display: none;
                flex-direction: row;
                align-items: center;
                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 18px;
                line-height: 21px;
                display: flex;
                align-items: center;
                color: #FFFFFF;
                margin: 5px 47px 0px 0px;
                img{
                    display: none;
                    margin: 0px 5px 0px 0px;
                }
                p{
                    display: none;
                    margin: 3px 0px 0px 0px;
                }
            }
            &__right    {
                display: flex;
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 16px;
                color: #FFFFFF;
                p{
                    margin: 11px -10px 0px 0px;
                }
            }
        }        
    }  
    .contacts-line-mob{
        display: flex;
        border: 1px solid #383050;
        width: 100%;
        margin-top: 20px;
    }
    .sub-footer-line-one{
        display: flex;
        border: 1px solid #383050;
        width: 100%;
    }
    .sub-footer-line-two{
        display: flex;
        border: 1px solid #383050;
        width: 100%;
    }
    .desktop-none{
        display: flex;
    }
}
@media (max-width: 375px) {
    .footer{
        height: 644px;
        background: #251C41;
        &__container{
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 0px 0px 0px 0px;
            &__cabinet{
                display: none;
                flex-direction: column;
                margin: 0px 0px 0px 2px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__menu{
                    display: flex;
                    flex-direction: column;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 24px;
                    color: #FFFFFF;
                    margin: 45px 0px 0px 0px;
                }
                &__text{
                    display: flex;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 12px;
                    line-height: 18px;
                    color: #FFFFFF;
                    margin: 40px 0px 0px 0px;
                }
                &__input{
                    display: flex;
                    margin: 5px 0px 0px -1px;
                    input[type="text"]{padding-left: 15px;}
                    input{
                        height: 40px;
                        width: 172px;
                        border: 0.813953px solid #C4C4C4;
                        box-sizing: border-box;
                        border-bottom-left-radius: 9px;
                        border-top-left-radius: 9px;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: normal;
                        font-size: 11.3953px;
                        line-height: 13px;
                        display: flex;
                        align-items: center;
                        color: #9B9B9B;
                        background-color: transparent;
                    }
                    &__box{
                        width: 38px;
                        height: 40px;
                        background: #97D513;
                        border: 0.813953px solid #C4C4C4;
                        box-sizing: border-box;
                        border-radius: 0px 9px 9px 0px;
                        display: flex;
                        justify-content: center;
                    }
                }
            }
            &__categories{
                display: none;
                flex-direction: column;
                margin: 2px 70px 0px 0px;
                width: 190px;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    color: #FFFFFF;
                }
                &__menu{
                    display: flex;
                    flex-direction: column;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 24px;
                    color: #FFFFFF;
                    margin: 43px 0px 0px 0px;
                }
            }
            &__store{
                display: flex;
                flex-direction: column;
                margin: 52px 0px 0px -2px;
                width: 190px;
                align-items: center;
                &__title{
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 24px;
                    line-height: 28px;
                    text-align: center;
                    color: #FFFFFF;
                    align-items: center;
                }
                &__menu{
                    align-items: center;
                    display: flex;
                    flex-direction: column;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 16px;
                    line-height: 30px;
                    text-align: center;
                    color: #FFFFFF;
                    margin: 23px 0px 0px -2px;
                }
            }
            &__contacts{
                display: flex;
                flex-direction: column;
                align-items: center;
                margin: 30px 0px 0px 0px;
                width: 256px;
                &__title{
                    align-items: center;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 24px;
                    line-height: 28px;
                    text-align: center;
                    color: #FFFFFF;
                    margin: 0px 0px 0px -2px;
                }
                &__bloks{
                    display: flex;
                    flex-direction: column;
                    align-items: center;
                    margin: 20px 0px 0px -13px;
                    &__block-phone{
                        display: flex;
                        flex-direction: row;
                        margin: 5px 0px 0px -2px;
                        &__button{
                            display: none;
                        }
                        &__text{
                            align-items: center;
                            display: flex;
                            flex-direction: column;
                            margin: 0px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 13px;
                                line-height: 15px;
                                color: #AEAEAE;
                                a{
                                    margin: 0px 0px 0px -5px;
                                    font-family: Roboto;
                                    font-style: normal;
                                    font-weight: bold;
                                    font-size: 24px;
                                    line-height: 28px;
                                    color: #FFFFFF;
                                }
                            }
                        }
                    }
                    &__block-address{
                        display: flex;
                        flex-direction: row;
                        margin: 14px 0px 0px -7px;
                        &__button{
                            display: none;
                            height: 40px;
                            width: 40px;
                            background: #97D413;
                            border-radius: 50%;
                            justify-content: center;
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            align-items: center;
                            margin: 2px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 14px;
                                line-height: 18px;
                                color: #FFFFFF;
                                a{
                                    margin: 0px 0px 0px 2px;
                                    font-weight: 600;
                                }
                            }
                        }
                    }
                    &__block-mail{
                        display: flex;
                        flex-direction: row;
                        margin: 18px 0px 0px 0px;
                        &__button{
                            display: none;
                            height: 40px;
                            width: 40px;
                            background: #97D413;
                            border-radius: 50%;
                            justify-content: center;
                            img{
                                margin: 5px 0px 0px 0px;
                            }
                        }
                        &__text{
                            display: flex;
                            flex-direction: column;
                            align-items: center;
                            margin: 0px 0px 0px 14px;
                            p{
                                font-family: Roboto;
                                font-style: normal;
                                font-weight: normal;
                                font-size: 14px;
                                line-height: 18px;
                                color: #FFFFFF;
                                a{      
                                    margin: 0px 0px 0px -5px;
                                    font-weight: 600;
                                }
                            }
                        }
                    }
                }
            }
            &__social{
                display: flex;
                flex-direction: row;
                margin: 21px 0px 0px -12px;
                align-items: center;
                &__icon{
                    display: flex;
                    width: 26px;
                    height: 26px;
                    border-radius: 50%;
                    margin: 0px 0px 0px 9px;
                }
            }
        }
    }
    .sub-footer{
        height: 81px;
        background: #251C41;
        &__container{
            display: flex;
            flex-direction: column-reverse;
            align-items: center;
            margin: 0px 0px 0px 0px;
            &__left{
                display: flex;
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 16px;
                text-align: right;
                color: #FFFFFF;
                margin: 16px 0px 0px 3px;
            }
            &__center{
                display: none;
                flex-direction: row;
                align-items: center;
                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 18px;
                line-height: 21px;
                display: flex;
                align-items: center;
                color: #FFFFFF;
                margin: 6px 47px 0px 0px;
                img{
                    display: none;
                    margin: 0px 5px 0px 0px;
                }
                p{
                    display: none;
                    margin: 3px 0px 0px 0px;
                }
            }
            &__right    {
                display: flex;
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 16px;
                color: #FFFFFF;
                p{
                    margin: 10px 0px 0px -5px;
                }
            }
        }        
    }  
    .contacts-line-mob{
        display: flex;
        border: 1px solid #383050;
        width: 100%;
        margin-top: 28px;
    }
    .sub-footer-line-one{
        display: flex;
        border: 1px solid #383050;
        width: 100%;
    }
    .sub-footer-line-two{
        display: flex;
        border: 1px solid #383050;
        width: 100%;
        margin: 4px 0px 0px 0px;
    }
    .desktop-none{
        display: flex;
    }
}
</style>