<template>
    <div>
      <div class="header">
          <div class="header__menu-top">
              <div class="header__menu-top-container">
              <div class="header__menu-top__logo-name">
                  <div><img src="../assets/image/Header/Vector.svg" /></div>
                  <div><a><img src="../assets/image/Header/AudioFree _.svg" /></a></div>
                  <div><p>Интернет магазин беспроводных наушников по РФ</p></div>
              </div>
              <div class="header__menu-top__menu">
                  <div><p>Доставка и оплата</p></div>
                  <div><p>Гарантия и возврат</p></div>
                  <div><p>Пункты самовывоза</p></div>
                  <div><p>Контакты</p></div>
              </div>
            </div>
          </div>
          <div class="header__menu-center container-header">
              <div class="header__menu-center__phone">
                  <div class="header__menu-center__phone__block">
                      <img src="../assets/image/Header/phone.svg" />
                    </div>
                  <div class="header__menu-center__phone__number-block">
                      <div class="header__menu-center__phone__number-block__call">
                          <p>Бесплатный звонок по РФ</p>
                        </div>
                      <div class="header__menu-center__phone__number-block__number">
                          <p>8 800 551-92-02</p>
                        </div>
                  </div>
              </div>
              <div class="header__menu-center__search">
                  <div class="header__menu-center__search__input">
                      <input type="text"  value="Поиск товара">
                  </div>
              </div>
            <div class="header__menu-center__button-icon">
                  <HeaderButton/>
          </div>
          </div>
          <hr>
          <div class="header__menu-bottom container-header">
              <div class="header__menu-bottom__menu-button">
                  <div class="header__menu-bottom__line"></div>
                  <div class="header__menu-bottom__menu-button__center">
                    <div><img src="../assets/image/Header/menu-icon.svg" /></div>
                    <div><p>Каталог товаров</p></div>
                </div>
                 <div class="header__menu-bottom__line"></div>
              </div>
              <div>
                  <div class="header__menu-bottom__menu">
                    <div><p>Главная</p></div>
                    <div><p>Скидки</p></div>
                    <div><p>Новинки</p></div>
                    <div><p>Бренды</p></div>
                    <div><p>Блог</p></div>
                    <div><p>Акции</p></div>
                </div>
              </div>
                <div class="header__menu-bottom__account">
                    <div class="header__menu-bottom__line"></div>
                    <div  class="header__menu-bottom__account__center">
                        <div><img src="../assets/image/Header/account.svg" /></div>
                        <div><p>Вход/Регистрация</p></div>
                    </div>
                    <div class="header__menu-bottom__line"></div>
                </div>
          </div>
      </div>
  <div class="header-mobile">
      <div class="header-mobile__container">
          <div class="header-mobile__container__menu-search">
            <div class="hamburger-menu">
              <input id="menu__toggle" type="checkbox" />
              <label class="menu__btn" for="menu__toggle">
                <span></span>
              </label>
              <ul class="menu__box">
                <li><a class="menu__item" href="#">О вебинаре</a></li>
                <li><a class="menu__item" href="#">Про спикера</a></li>
                <li><a class="menu__item" href="#">Узнать больше</a></li>
              </ul>
            </div>
            <div>
                <img src="../assets/image/Header/search.svg" />
            </div>
          </div>
          <div class="header-mobile__container__logo">
              <p>AudioFree</p>
            </div>
          <div>
            <div class="header-mobile__container__icon-menu">
                <div class="header-mobile__container__icon-menu__phone">
                    <img src="../assets/image/Header/phone.svg" />
                </div>
                <div class="header-mobile__container__icon-menu__block-icon">
                    <div class="header-mobile__container__icon-menu__green"><p>1</p></div>
                  <img src="../assets/image/Header/shop.svg" />
                </div>
                <div class="header-mobile__container__icon-menu__block-icon">
                    <div class="header-mobile__container__icon-menu__green"><p>1</p></div>
                  <img src="../assets/image/Header/accountmob.svg" />
                </div>
            </div>
          </div>
      </div>
  </div>
    </div>
</template>

<script>

import HeaderButton from "@/components/HeaderButton"

export default {
    components: {
        HeaderButton
    }
}
</script>

<style lang="scss">
    .header{
        display: flex;
        flex-direction: column;
        height: 165px;
        background-color: #ffffff;
        hr{
            border: 1px solid #E7E7E7;
        }
        &__menu-top-container{
            display: flex;
            justify-content: space-between;
            width: 1172px;
            margin: 0px 0px 0px 373px;
        }
        &__menu-top{
            background: #251C41;
            height: 30px;
            color: #ffffff;
            display: flex;
            &__logo-name{
                display: flex;
                align-items: center;
                a{
                    margin-left: 8px;
                }
                img{
                    margin-top: 5px;
                    margin-left: 1px;
                }
                p{
                    margin-left: 8px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 13px;
                    line-height: 15px;
                    display: flex;
                    align-items: center;
                    color: #FFFFFF; 
                }
            }
             &__menu{
                display: flex;
                align-items: center;
                p{
                    margin-left: 30px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 13px;
                    line-height: 15px;
                    color: #FFFFFF;
                }
            }
        }
        &__menu-center{
            height: 93px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            &__phone{
                display: flex;
                &__block{
                    margin-left: 2px;
                    display: flex;
                    height: 38px;
                    width: 38px;
                    background: #FFFFFF;
                    box-shadow: 0px 5.81081px 15.1081px rgba(140, 121, 199, 0.3);
                    border-radius: 25.5676px;
                    img{
                        margin: 0px 0px 0px 5px;
                    }
                }
                &__number-block{
                    display: flex;
                    flex-direction: column;
                    margin-left: 15px;
                    &__call{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: normal;
                        font-size: 13px;
                        line-height: 15px;
                        color: #AEAEAE;
                    }
                    &__number{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: bold;
                        font-size: 24px;
                        line-height: 28px;
                        color: #313131;
                    }
                }
            }  
            &__search{
                display: flex;
                margin: 0px 0px 0px 5px;
                &__input{
                    input[type="text"]{padding-left: 40px;}
                    input{
                        display: flex;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: 500;
                        font-size: 18px;
                        line-height: 21px;
                        color: #474747;
                        display: flex;
                        border-style: none;
                        width: 312px;
                        height: 38px;
                        background: #FCFCFC;
                        border: 1.15152px solid #D9D9D9;
                        box-sizing: border-box;
                        border-radius: 23.0303px;
                        background-image: url("../assets/image/Header/search.svg");
                        background-repeat: no-repeat;
                        background-position: 3% 55%;
                    }
                }
            }
            &__button-icon{
                margin: 0px 1px 0px 0px;
            }
        }
        &__menu-bottom{
            height: 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 1174px;
            &__line{
                height: 40px;
                border: 1px solid #E7E7E7;
                transform: rotate(180deg);
            }
            &__menu-button{
                display: flex;
                justify-content: space-between;  
                align-items: center;
                width: 30%;
                img{
                    padding: 0px 30px 0px 0px;
                    display: flex;
                    align-items: center;
                }
                p{
                    padding: 0px 0px 3px 0px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    text-align: center;
                    color: #474747;
                }
                &__center{
                    display: flex;
                    flex-direction: row;
                    margin-right: 45px;
                }
            }
            &__menu{
                display: flex;
                width: 40%;
                padding-left: 90px;
                p{
                    height: 40px;
                    margin-right: 38px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: bold;
                    font-size: 14px;
                    line-height: 16px;
                    color: #404040;
                    border-bottom: 3px solid transparent;
                    padding-top: 10px;
                }
                p:hover{
                    height: 40px;
                    border-bottom: 3px solid #97D513;
                    color: #97D513;
                }
            }
            &__account{
                display: flex;
                justify-content: space-between;
                align-items: center;
                margin-left: 30px;
                width: 30%;
                &__center{
                    display: flex;
                    flex-direction: row;
                    margin-right: 3px;
                }
                p{
                    display: flex;
                    margin-left: 9px;
                    margin-top: 3px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 16px;
                    color: #353535;
                }
            }
        }
    }
    .header-mobile{
        display: none;
    }
    //hamburger-menu
    .hamburger-menu {
    display: flex;
    position: relative;
  }
  /* скрываем чекбокс */
  #menu__toggle {
    opacity: 0;
  }
  /* стилизуем кнопку */
  .menu__btn {
    display: flex; /* используем flex для центрирования содержимого */
    align-items: center; /* центрируем содержимое кнопки */
    position: fixed;
    top: 10px;
    left: 20px;
    width: 26px;
    height: 26px;
    cursor: pointer;
    z-index: 1;
  }
  /* добавляем "гамбургер" */
  .menu__btn > span,
  .menu__btn > span::before,
  .menu__btn > span::after {
    display: block;
    position: absolute;
    width: 100%;
    height: 2px;
    background-color: #251C41;
  }
  .menu__btn > span::before {
    content: "";
    top: -8px;
  }
  .menu__btn > span::after {
    content: "";
    top: 8px;
  }
  /* контейнер меню */
  .menu__box {
    display: block;
    position: fixed;
    visibility: hidden;
    top: 0;
    left: -100%;
    width: 300px;
    height: 100%;
    margin: 0;
    padding: 80px 0;
    list-style: none;
    text-align: center;
    background-color: #eceff1;
    box-shadow: 1px 0px 6px rgba(0, 0, 0, 0.2);
  }
  /* элементы меню */
  .menu__item {
    display: block;
    padding: 12px 24px;
    color: #333;
    font-family: "Roboto", sans-serif;
    font-size: 20px;
    font-weight: 600;
    text-decoration: none;
  }
  .menu__item:hover {
    background-color: #cfd8dc;
  }
  #menu__toggle:checked ~ .menu__btn > span {
    transform: rotate(45deg);
  }
  #menu__toggle:checked ~ .menu__btn > span::before {
    top: 0;
    transform: rotate(0);
  }
  #menu__toggle:checked ~ .menu__btn > span::after {
    top: 0;
    transform: rotate(90deg);
  }
  #menu__toggle:checked ~ .menu__box {
    visibility: visible;
    left: 0;
  }
@media (max-width: 1580px) {
        .header{
        display: flex;
        flex-direction: column;
        height: 165px;
        background-color: #ffffff;
        hr{
            border: 1px solid #E7E7E7;
        }
        &__menu-top-container{
            display: flex;
            justify-content: space-between;
            width: 1172px;
            margin: 0px 0px 0px 150px;
        }
    }
        .header-mobile{
        display: none;
    }
}
@media (max-width: 1224px) {
        .header{
        display: flex;
        flex-direction: column;
        height: 165px;
        background-color: #ffffff;
        hr{
            border: 1px solid #E7E7E7;
        }
        &__menu-top-container{
            display: flex;
            justify-content: space-between;
            width: 1172px;
            margin: 0px 0px 0px 10px;
        }
    }
        .header-mobile{
        display: none;
    }
}
@media (max-width: 1024px) {
        .header{
        display: flex;
        flex-direction: column;
        height: 165px;
        background-color: #ffffff;
        hr{
            border: 1px solid #E7E7E7;
        }
        &__menu-top-container{
            display: flex;
            justify-content: space-evenly;
            width: 1024px;
            margin: 0px 0px 0px 10px;
        }
        &__menu-top{
            background: #251C41;
            height: 30px;
            color: #ffffff;
            display: flex;
            &__logo-name{
                display: flex;
                align-items: center;
                a{
                    margin-left: 8px;
                }
                img{
                    margin-top: 5px;
                    margin-left: 1px;
                }
                p{
                    margin-left: 8px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 13px;
                    line-height: 15px;
                    display: flex;
                    align-items: center;
                    color: #FFFFFF; 
                }
            }
             &__menu{
                display: flex;
                align-items: center;
                p{
                    margin-left: 10px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 13px;
                    line-height: 15px;
                    color: #FFFFFF;
                }
            }
        }
        &__menu-center{
            height: 93px;
            display: flex;
            justify-content: space-evenly;
            align-items: center;
            margin-left: -20px;
            &__phone{
                display: flex;
                &__block{
                    margin-left: 2px;
                    display: flex;
                    height: 38px;
                    width: 38px;
                    background: #FFFFFF;
                    box-shadow: 0px 5.81081px 15.1081px rgba(140, 121, 199, 0.3);
                    border-radius: 25.5676px;
                    img{
                        margin: 0px 0px 0px 5px;
                    }
                }
                &__number-block{
                    display: flex;
                    flex-direction: column;
                    margin-left: 15px;
                    &__call{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: normal;
                        font-size: 13px;
                        line-height: 15px;
                        color: #AEAEAE;
                    }
                    &__number{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: bold;
                        font-size: 24px;
                        line-height: 28px;
                        color: #313131;
                    }
                }
            }  
            &__search{
                display: flex;
                margin: 0px 0px 0px 5px;
                &__input{
                    input[type="text"]{padding-left: 40px;}
                    input{
                        display: flex;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: 500;
                        font-size: 18px;
                        line-height: 21px;
                        color: #474747;
                        display: flex;
                        border-style: none;
                        width: 312px;
                        height: 38px;
                        background: #FCFCFC;
                        border: 1.15152px solid #D9D9D9;
                        box-sizing: border-box;
                        border-radius: 23.0303px;
                        background-image: url("../assets/image/Header/search.svg");
                        background-repeat: no-repeat;
                        background-position: 3% 55%;
                    }
                }
            }
            &__button-icon{
                margin: 0px 1px 0px 0px;
            }
        }
        &__menu-bottom{
            height: 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 1024px;
            &__line{
                height: 40px;
                border: 1px solid #E7E7E7;
                transform: rotate(180deg);
            }
            &__menu-button{
                display: flex;
                justify-content: space-between;  
                align-items: center;
                width: 30%;
                img{
                    padding: 0px 10px 0px 0px;
                    display: flex;
                    align-items: center;
                }
                p{
                    padding: 0px 0px 3px 0px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    text-align: center;
                    color: #474747;
                }
                &__center{
                    display: flex;
                    flex-direction: row;
                    margin-right: 0px;
                }
            }
            &__menu{
                display: flex;
                width: 40%;
                padding-left: 90px;
                p{
                    height: 40px;
                    margin-right: 38px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: bold;
                    font-size: 14px;
                    line-height: 16px;
                    color: #404040;
                    border-bottom: 3px solid transparent;
                    padding-top: 10px;
                }
                p:hover{
                    height: 40px;
                    border-bottom: 3px solid #97D513;
                    color: #97D513;
                }
            }
            &__account{
                display: flex;
                justify-content: space-between;
                align-items: center;
                margin-left: 30px;
                width: 30%;
                &__center{
                    display: flex;
                    flex-direction: row;
                    margin-right: 3px;
                }
                p{
                    display: flex;
                    margin-left: 9px;
                    margin-top: 3px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 16px;
                    color: #353535;
                }
            }
        }
    }
        .header-mobile{
        display: none;
    }
}
@media (max-width: 768px) {
        .header{
        display: flex;
        flex-direction: column;
        height: 165px;
        background-color: #ffffff;
        hr{
            border: 1px solid #E7E7E7;
        }
        &__menu-top-container{
            display: flex;
            justify-content: space-evenly;
            width: 1024px;
            margin: 0px 0px 0px 10px;
        }
        &__menu-top{
            background: #251C41;
            height: 30px;
            color: #ffffff;
            display: flex;
            flex-direction: row;
            &__logo-name{
                display: flex;
                align-items: center;
                a{
                    margin-left: 8px;
                }
                img{
                    margin-top: 5px;
                    margin-left: 1px;
                }
                p{
                    margin-left: 8px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 13px;
                    line-height: 15px;
                    display: flex;
                    align-items: center;
                    color: #FFFFFF; 
                }
            }
             &__menu{
                display: flex;
                align-items: center;
                margin-left: -30px;
                p{
                    margin-left: 5px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 13px;
                    line-height: 15px;
                    color: #FFFFFF;
                }
            }
        }
        &__menu-center{
            height: 93px;
            display: flex;
            justify-content: space-evenly;
            align-items: center;
            margin-left: 0px;
            &__phone{
                display: flex;
                &__block{
                    margin-left: 2px;
                    display: flex;
                    height: 38px;
                    width: 38px;
                    background: #FFFFFF;
                    box-shadow: 0px 5.81081px 15.1081px rgba(140, 121, 199, 0.3);
                    border-radius: 25.5676px;
                    img{
                        margin: 0px 0px 0px 5px;
                    }
                }
                &__number-block{
                    display: flex;
                    flex-direction: column;
                    margin-left: 15px;
                    &__call{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: normal;
                        font-size: 13px;
                        line-height: 15px;
                        color: #AEAEAE;
                    }
                    &__number{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: bold;
                        font-size: 24px;
                        line-height: 28px;
                        color: #313131;
                    }
                }
            }  
            &__search{
                display: flex;
                margin: 0px 0px 0px 5px;
                &__input{
                    input[type="text"]{padding-left: 40px;}
                    input{
                        display: flex;
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: 500;
                        font-size: 18px;
                        line-height: 21px;
                        color: #474747;
                        display: flex;
                        border-style: none;
                        width: 312px;
                        height: 38px;
                        background: #FCFCFC;
                        border: 1.15152px solid #D9D9D9;
                        box-sizing: border-box;
                        border-radius: 23.0303px;
                        background-image: url("../assets/image/Header/search.svg");
                        background-repeat: no-repeat;
                        background-position: 3% 55%;
                    }
                }
            }
            &__button-icon{
                margin: 0px 1px 0px -30px;
            }
        }
        &__menu-bottom{
            height: 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 768px;
            &__line{
                height: 40px;
                border: 1px solid #E7E7E7;
                transform: rotate(180deg);
            }
            &__menu-button{
                display: flex;
                justify-content: space-between;  
                align-items: center;
                width: 20%;
                img{
                    padding: 0px 10px 0px 0px;
                    display: flex;
                    align-items: center;
                }
                p{
                    padding: 0px 0px 3px 0px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 18px;
                    line-height: 21px;
                    text-align: center;
                    color: #474747;
                    display: none;
                }
                &__center{
                    display: flex;
                    flex-direction: row;
                    margin-right: 0px;
                }
            }
            &__menu{
                display: flex;
                width: 50%;
                padding-left: 10px;
                p{
                    height: 40px;
                    margin-right: 28px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: bold;
                    font-size: 14px;
                    line-height: 16px;
                    color: #404040;
                    border-bottom: 3px solid transparent;
                    padding-top: 10px;
                }
                p:hover{
                    height: 40px;
                    border-bottom: 3px solid #97D513;
                    color: #97D513;
                }
            }
            &__account{
                display: flex;
                justify-content: space-between;
                align-items: center;
                margin-left: -25px;
                width: 30%;
                &__center{
                    display: flex;
                    flex-direction: row;
                    margin-right: 3px;
                }
                p{
                    display: flex;
                    margin-left: 9px;
                    margin-top: 3px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 16px;
                    color: #353535;
                }
            }
        }
    }
        .header-mobile{
        display: none;
    }
}
@media (max-width: 415px) {
    .header-mobile{
        display: flex;
        width: 414px;
        height: 50px;
        border-bottom-right-radius: 9.5px;
        border-bottom-left-radius: 9.5px;
        background: #FFFFFF;
        position: fixed;
        z-index: 10;
        &__container{
            display: flex;
            margin: 0px 10px 0px 10px;
            justify-content: space-between;
            width: 100%;
            &__menu-search{
                display: flex;
                flex-direction: row;
                align-items: center;
                img{
                    padding-left: 40px;
                }
            }
            &__logo{
                display: flex;
                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 18px;
                line-height: 21px;
                display: flex;
                align-items: center;
                color: #251C41;
            }
            &__icon-menu{
                display: flex;
                align-items: center;
                margin: 10px 0px 0px 0px;
                &__phone{
                    display: flex;
                    margin: 0px 10px 0px 0px;
                }
                &__block-icon{
                    position: relative;
                    margin: 0px 10px 0px 0px;
                    img{
                        margin: 0px 0px 0px 5px;
                    }
                }
                &__green{
                    display: flex;
                    position: absolute;
                    z-index: 3;
                    height: 16px;
                    width: 16px;
                    background: #34C900;
                    border-radius: 21.0556px;
                    margin: -5px 0px 0px 20px;
                    p{
                         font-family: Roboto;
                         font-style: normal;
                         font-weight: bold;
                         font-size: 11.4849px;
                         line-height: 13px;
                         display: flex;
                         align-items: center;
                         color: #FFFFFF;
                         margin-left: 5px;
                    }
                }
            }
        }
    }
    .header{
        display: none;
    }
}

//iphone 6/7/8 PerfectPixel

@media (max-width: 375px) {
    .header-mobile{
        display: flex;
        width: 375px;
        height: 50px;
        border-bottom-right-radius: 9.5px;
        border-bottom-left-radius: 9.5px;
        background: #FFFFFF;
        position: fixed;
        z-index: 10;
        &__container{
            display: flex;
            margin: 0px 10px 0px 10px;
            justify-content: space-between;
            width: 100%;
            &__menu-search{
                display: flex;
                flex-direction: row;
                align-items: center;
                img{
                    padding: 5px 0px 0px 30px;
                }
            }
            &__logo{
                display: flex;
                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 18px;
                line-height: 21px;
                display: flex;
                align-items: center;
                color: #251C41;
                margin: 0px 0px 0px 34px;
            }
            &__icon-menu{
                display: flex;
                align-items: center;
                margin: 10px 0px 0px 0px;
                &__phone{
                    display: flex;
                    margin: 0px 8px 0px 0px;
                }
                &__block-icon{
                    position: relative;
                    margin: 2px 6px 0px 0px;
                    img{
                        margin: 0px 0px 0px 7px;
                    }
                }
                &__green{
                    display: flex;
                    position: absolute;
                    z-index: 3;
                    height: 14px;
                    width: 14px;
                    background: #34C900;
                    border-radius: 21.0556px;
                    margin: -5px 0px 0px 23px;
                    p{
                        font-family: Roboto;
                        font-style: normal;
                        font-weight: bold;
                        font-size: 9.82514px;
                        line-height: 12px;
                        display: flex;
                        align-items: center;
                        color: #FFFFFF;
                        margin-left: 5px;
                    }
                }
            }
        }
    }
    .header{
        display: none;
    }
        //hamburger-menu
    .hamburger-menu {
    display: flex;
    position: relative;
  }
  /* скрываем чекбокс */
  #menu__toggle {
    opacity: 0;
  }
  /* стилизуем кнопку */
  .menu__btn {
    display: flex; /* используем flex для центрирования содержимого */
    align-items: center; /* центрируем содержимое кнопки */
    position: fixed;
    top: 11px;
    left: 16px;
    width: 23px;
    height: 29px;
    cursor: pointer;
    z-index: 1;
  }
  /* добавляем "гамбургер" */
  .menu__btn > span,
  .menu__btn > span::before,
  .menu__btn > span::after {
    display: block;
    position: absolute;
    width: 100%;
    height: 2px;
    background-color: #251C41;
  }
  .menu__btn > span::before {
    content: "";
    top: -8px;
  }
  .menu__btn > span::after {
    content: "";
    top: 8px;
  }
  /* контейнер меню */
  .menu__box {
    display: block;
    position: fixed;
    visibility: hidden;
    top: 0;
    left: -100%;
    width: 300px;
    height: 100%;
    margin: 0;
    padding: 80px 0;
    list-style: none;
    text-align: center;
    background-color: #eceff1;
    box-shadow: 1px 0px 6px rgba(0, 0, 0, 0.2);
  }
  /* элементы меню */
  .menu__item {
    display: block;
    padding: 12px 24px;
    color: #333;
    font-family: "Roboto", sans-serif;
    font-size: 20px;
    font-weight: 600;
    text-decoration: none;
  }
  .menu__item:hover {
    background-color: #cfd8dc;
  }
  #menu__toggle:checked ~ .menu__btn > span {
    transform: rotate(45deg);
  }
  #menu__toggle:checked ~ .menu__btn > span::before {
    top: 0;
    transform: rotate(0);
  }
  #menu__toggle:checked ~ .menu__btn > span::after {
    top: 0;
    transform: rotate(90deg);
  }
  #menu__toggle:checked ~ .menu__box {
    visibility: visible;
    left: 0;
  }
}
@media (max-width: 360px) {
    .header-mobile{
        display: flex;
        width: 360px;
        height: 50px;
        border-bottom-right-radius: 9.5px;
        border-bottom-left-radius: 9.5px;
        background: #FFFFFF;
        position: fixed;
        z-index: 10;
        &__container{
            display: flex;
            margin: 0px 10px 0px 10px;
            justify-content: space-between;
            width: 100%;
            &__menu-search{
                display: flex;
                flex-direction: row;
                align-items: center;
                img{
                    padding: 5px 0px 0px 30px;
                }
            }
            &__logo{
                display: flex;
                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 18px;
                line-height: 21px;
                display: flex;
                align-items: center;
                color: #251C41;
                margin: 0px 0px 0px 35px;
            }
            &__icon-menu{
                display: flex;
                align-items: center;
                margin: 10px 0px 0px 0px;
                &__phone{
                    display: flex;
                    margin: 0px 0px 0px 0px;
                }
                &__block-icon{
                    position: relative;
                    margin: 2px 0px 0px 0px;
                    img{
                        margin: 0px 0px 0px 10px;
                    }
                }
                &__green{
                    display: flex;
                    position: absolute;
                    z-index: 3;
                    height: 16px;
                    width: 16px;
                    background: #34C900;
                    border-radius: 21.0556px;
                    margin: -5px 0px 0px 25px;
                    p{
                         font-family: Roboto;
                         font-style: normal;
                         font-weight: bold;
                         font-size: 11.4849px;
                         line-height: 13px;
                         display: flex;
                         align-items: center;
                         color: #FFFFFF;
                         margin-left: 5px;
                    }
                }
            }
        }
    }
    .header{
        display: none;
    }
        //hamburger-menu
    .hamburger-menu {
    display: flex;
    position: relative;
  }
  /* скрываем чекбокс */
  #menu__toggle {
    opacity: 0;
  }
  /* стилизуем кнопку */
  .menu__btn {
    display: flex; /* используем flex для центрирования содержимого */
    align-items: center; /* центрируем содержимое кнопки */
    position: fixed;
    top: 11px;
    left: 16px;
    width: 23px;
    height: 29px;
    cursor: pointer;
    z-index: 1;
  }
  /* добавляем "гамбургер" */
  .menu__btn > span,
  .menu__btn > span::before,
  .menu__btn > span::after {
    display: block;
    position: absolute;
    width: 100%;
    height: 2px;
    background-color: #251C41;
  }
  .menu__btn > span::before {
    content: "";
    top: -8px;
  }
  .menu__btn > span::after {
    content: "";
    top: 8px;
  }
  /* контейнер меню */
  .menu__box {
    display: block;
    position: fixed;
    visibility: hidden;
    top: 0;
    left: -100%;
    width: 300px;
    height: 100%;
    margin: 0;
    padding: 80px 0;
    list-style: none;
    text-align: center;
    background-color: #eceff1;
    box-shadow: 1px 0px 6px rgba(0, 0, 0, 0.2);
  }
  /* элементы меню */
  .menu__item {
    display: block;
    padding: 12px 24px;
    color: #333;
    font-family: "Roboto", sans-serif;
    font-size: 20px;
    font-weight: 600;
    text-decoration: none;
  }
  .menu__item:hover {
    background-color: #cfd8dc;
  }
  #menu__toggle:checked ~ .menu__btn > span {
    transform: rotate(45deg);
  }
  #menu__toggle:checked ~ .menu__btn > span::before {
    top: 0;
    transform: rotate(0);
  }
  #menu__toggle:checked ~ .menu__btn > span::after {
    top: 0;
    transform: rotate(90deg);
  }
  #menu__toggle:checked ~ .menu__box {
    visibility: visible;
    left: 0;
  }
}
</style>