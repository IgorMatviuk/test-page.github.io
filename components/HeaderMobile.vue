<template>
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
</template>

<script>

export default {
}
</script>

<style lang="scss" scoped>
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
</style>