<template>
  <div class="brand-card">
      <div class="brand-card__brand-block">
          <div class="brand-card__brand-block__image1"></div>
          <div class="brand-card__brand-block__text"><p>Для iphone</p></div>
          <div class="brand-card__brand-block__border"></div>
      </div>
        <div class="brand-card__brand-block">
          <div class="brand-card__brand-block__image2"></div>
          <div class="brand-card__brand-block__text"><p>Для Samsung</p></div>
          <div class="brand-card__brand-block__border"></div>
      </div>
        <div class="brand-card__brand-block mobile-magrin-button">
          <div class="brand-card__brand-block__image3"></div>
          <div class="brand-card__brand-block__text"><p>Для Xiaomi</p></div>
          <div class="brand-card__brand-block__border"></div>
      </div>
        <div class="brand-card__brand-block mobile-magrin-left">
          <div class="brand-card__brand-block__image4"></div>
          <div class="brand-card__brand-block__text"><p>Для Huawei</p></div>
          <div class="brand-card__brand-block__border"></div>
      </div>
        <div class="brand-card__brand-block mobile-magrin-left">
          <div class="brand-card__brand-block__image5"></div>
          <div class="brand-card__brand-block__text"><p>Со скидкой</p></div>
          <div class="brand-card__brand-block__border"></div>
      </div>
      <div class="brand-card__all-brand">
          <img class="display-none" src="./ProductBrand/Group 282.png" />
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .brand-card{
        display: flex;
        flex-direction: column;
        margin: -13px 0px 0px 8px;
        &__brand-block{
            display: flex;
            justify-content: space-between;
            width: 268px;
            height: 56px;
            background: #FFFFFF;
            box-shadow: 0px 0px 18px rgba(0, 0, 0, 0.07);
            border-radius: 9.5px;
            margin-top: 14px;
            &__text{
                display: flex;
                align-items: center;
                font-family: Roboto;
                font-style: normal;
                font-weight: 500;
                font-size: 14px;
                line-height: 16px;
                color: #353535;
                margin: 2px 100px 0px 0px;
            }
            &__border{
                background: #DFDFDF;
                border-radius: 0px 8px 8px 0px;
                width: 5px;
            }
            &__border:hover{
                background: #816BC2;
                border-radius: 0px 8px 8px 0px;
                width: 5px;
            }
            &__image1{
                background-image: url("ProductBrand/apple.svg");
                background-repeat: no-repeat;
                background-position: 3% 55%;
                width: 50px;
                height: 50px;
                display: flex;
                align-items: center;
                margin: 0px 0px 0px 22px;
            }
            &__image2{
                background-image: url("ProductBrand/samsung.svg");
                background-repeat: no-repeat;
                background-position: 3% 55%;
                width: 50px;
                height: 50px;
                display: flex;
                align-items: center;
                margin: 0px 0px 0px 22px;
            }
            &__image3{
                background-image: url("ProductBrand/mi.svg");
                background-repeat: no-repeat;
                background-position: 3% 55%;
                width: 50px;
                height: 50px;
                display: flex;
                align-items: center;
                margin: 0px 0px 0px 22px;
            }
            &__image4{
                background-image: url("ProductBrand/hu.svg");
                background-repeat: no-repeat;
                background-position: 3% 55%;
                width: 50px;
                height: 50px;
                display: flex;
                align-items: center;
                margin: 0px 0px 0px 22px;
            }
            &__image5{
                background-image: url("ProductBrand/sale.svg");
                background-repeat: no-repeat;
                background-position: 3% 55%;
                width: 50px;
                height: 50px;
                display: flex;
                align-items: center;
                margin: 0px 0px 0px 22px;
            }
            &__image1:hover{
                background-image: url("ProductBrand/appleV.svg");
            }
            &__image2:hover{
                background-image: url("ProductBrand/samsungV.svg");
            }
            &__image3:hover{
                background-image: url("ProductBrand/miV.svg");
            }
            &__image4:hover{
                background-image: url("ProductBrand/huV.svg");
            }
            &__image5:hover{
                background-image: url("ProductBrand/saleV.svg");
            }
        }
        &__all-brand{
            display: flex;
            img{
                height: 135px;
                margin: -4px 0px 0px -19px;
            }
        }
    }
    @media (max-width: 375px) {
    .brand-card{
        display: flex;
        flex-wrap: wrap;
        margin: 8px 0px 0px 8px;
        width: 375px;
        height: 240px;
        &__brand-block{
            display: flex;
            justify-content: space-between;
            width: 175px;
            height: 56px;
            background: #FFFFFF;
            box-shadow: 0px 0px 18px rgba(0, 0, 0, 0.07);
            border-radius: 9.5px;
            margin-top: 6px;
            &__text{
                display: flex;
                align-items: center;
                font-family: Roboto;
                font-style: normal;
                font-weight: 500;
                font-size: 14px;
                line-height: 16px;
                color: #353535;
                margin: 2px 0px 0px -40px;
            }
            &__border{
                background: #DFDFDF;
                border-radius: 0px 8px 8px 0px;
                width: 5px;
            }
            &__border:hover{
                background: #816BC2;
                border-radius: 0px 8px 8px 0px;
                width: 5px;
            }
            &__image1{
                background-image: url("ProductBrand/apple.svg");
                background-repeat: no-repeat;
                background-position: 3% 55%;
                width: 50px;
                height: 50px;
                display: flex;
                align-items: center;
                margin: 0px 0px 0px 22px;
            }
            &__image2{
                background-image: url("ProductBrand/samsung.svg");
                background-repeat: no-repeat;
                background-position: 3% 55%;
                width: 50px;
                height: 50px;
                display: flex;
                align-items: center;
                margin: 0px 0px 0px 22px;
            }
            &__image3{
                background-image: url("ProductBrand/mi.svg");
                background-repeat: no-repeat;
                background-position: 3% 55%;
                width: 50px;
                height: 50px;
                display: flex;
                align-items: center;
                margin: 0px 0px 0px 22px;
            }
            &__image4{
                background-image: url("ProductBrand/hu.svg");
                background-repeat: no-repeat;
                background-position: 3% 55%;
                width: 50px;
                height: 50px;
                display: flex;
                align-items: center;
                margin: 0px 0px 0px 22px;
            }
            &__image5{
                background-image: url("ProductBrand/sale.svg");
                background-repeat: no-repeat;
                background-position: 3% 55%;
                width: 50px;
                height: 50px;
                display: flex;
                align-items: center;
                margin: 0px 0px 0px 22px;
            }
            &__image1:hover{
                background-image: url("ProductBrand/appleV.svg");
            }
            &__image2:hover{
                background-image: url("ProductBrand/samsungV.svg");
            }
            &__image3:hover{
                background-image: url("ProductBrand/miV.svg");
            }
            &__image4:hover{
                background-image: url("ProductBrand/huV.svg");
            }
            &__image5:hover{
                background-image: url("ProductBrand/saleV.svg");
            }
        }
        &__all-brand{
            display: flex;
            width: 190px;
            height: 77px;
            background-image: url("ProductBrand/Component 40.png");
            background-repeat: no-repeat;
            margin: 0px 0px 0px -20px;
            img{
                width: 0px;
                height: 0px;
            }
        }
    } 
    .mobile-magrin-button{
        margin-top: 14px;
    }
    .mobile-magrin-left{
        margin-left: -8px;
    }
    .display-none{
    display: none;
    }    
}
</style>