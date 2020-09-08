<template>
  <div class="sale-card">
      <div class="sale-card__sale-block">
        <div class="sale-card__sale-block__image">
              <img src="./ProductSale/Rectangle 148.png" />
        </div>
        <div  class="sale-card__sale-block__title"><p>Распродажа</p></div>
        <div  class="sale-card__sale-block__text"><p>За прошедшие годы текст Lorem Ipsum получил много версий. Некоторые версии появились по ошибке, некоторые - намеренно</p></div>
        <div  class="sale-card__sale-block__button">
            <button><p>В каталог скидок</p></button>
        </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .sale-card{
        display: flex;
        flex-direction: column;
        margin: 18px 0px 0px -25px;
        &__sale-block{
            display: flex;
            flex-direction: column;
            width: 270px;
            height: 441px;
            background: #8B75C8;
            box-shadow: 0px 4px 18px rgba(0, 0, 0, 0.1);
            border-radius: 9px;
            &__image{
                display: flex;
                margin: 34px 0px 0px 27px;
            }
            &__title{
                display: flex;
                margin: 26px 0px 0px 26px;
                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 24px;
                line-height: 28px;
                color: #FFFFFF;
            }
            &__text{
                display: flex;
                margin: 13px 0px 0px 25px;
                font-family: Roboto;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 20px;
                color: #FFFFFF;
            }
            &__button{
                button{
                    display: flex;
                    align-items: center;
                    width: 221px;
                    height: 52px;
                    margin: 26px 0px 0px 26px;
                    background: linear-gradient(180deg, rgba(255, 255, 255, 0) 0%, #91CF0D 100%), #97D413;
                    border: 1px solid #97D413;
                    box-sizing: border-box;
                    border-radius: 220px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: bold;
                    font-size: 14px;
                    line-height: 16px;
                    text-align: center;
                    color: #FFFFFF;
                    p{
                        margin: 4px 0px 0px 45px;
                    }
                }
            }
        }
    }
@media (max-width: 414px) {
    .sale-card{
        display: none;
        width: 0px;
        height: 0px;
    }
}
</style>