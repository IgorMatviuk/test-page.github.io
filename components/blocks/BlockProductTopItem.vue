<template>
  <div class="card">
    <div class="card__container">
      <div class="mob-image desktop-none">
        <div class="mob-image__prod">
          <img src="./Top/besprovodnye-mob.png" />
        </div>
        <div class="mob-image__plus">
          <img src="./Top/plus.svg" />
        </div>
      </div>
      <div class="card__container__image">
        <img src="./Top/besprovodnye.png" />
      </div>
      <div class="mob-title desktop-none">
        <p>{{ content.titleMob }}</p>
      </div>
      <div class="card__container__right">
        <div class="card__container__right__title">
          <p>{{ content.title }}</p>
        </div>
        <div class="card__container__right__star">
          <img src="@/components/blocks/BlockProductOneClick/star-active.svg"/>
          <img src="@/components/blocks/BlockProductOneClick/star-active.svg"/>
          <img src="@/components/blocks/BlockProductOneClick/star-active.svg"/>
          <img src="@/components/blocks/BlockProductOneClick/star-active.svg"/>
          <img src="@/components/blocks/BlockProductOneClick/star.svg"/>   
        </div>
        <div class="card__container__right__price">
          <p>{{ content.price }}</p>
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
    display: flex;
    width: 387px;
    height: 162px;
    margin: 27px 0px 0px 17px;
    background: #FFFFFF;
    box-shadow: 0px 0px 10.5556px rgba(0, 0, 0, 0.05);
    border-radius: 9.5px;
    &__container{
      display: flex;
      flex-direction: row;
      margin: 22px 0px 0px 0px;
      &__image{
        margin: 0px 0px 0px 2px;
      }
      &__right{
        display: flex;
        flex-direction: column;
        margin: 5px 0px 0px 12px;
        &__title{
          display: flex;
          font-family: Roboto;
          font-style: normal;
          font-weight: 700;
          font-size: 14px;
          line-height: 20px;
          color: #353535;
        }
        &__star{
          display: flex;
          margin: 7px 0px 0px -6px;
          img{
            margin: 0px 0px 0px 4px;
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
          margin: 14px 0px 0px 0px;
        }
      }
    }
  }
  .desktop-none{
    display: none;
  }
@media (max-width: 768px) {
  .card{
    display: flex;
    width: 300px;
    height: 162px;
    margin: 25px 0px 0px 17px;
    background: #FFFFFF;
    box-shadow: 0px 0px 10.5556px rgba(0, 0, 0, 0.05);
    border-radius: 9.5px;
    &__container{
      display: flex;
      flex-direction: row;
      margin: 22px 0px 0px 0px;
      &__image{
        margin: 0px 0px 0px 2px;
      }
      &__right{
        display: flex;
        flex-direction: column;
        margin: 5px 0px 0px 12px;
        &__title{
          display: flex;
          font-family: Roboto;
          font-style: normal;
          font-weight: 700;
          font-size: 14px;
          line-height: 20px;
          color: #353535;
        }
        &__star{
          display: flex;
          margin: 7px 0px 0px -6px;
          img{
            margin: 0px 0px 0px 4px;
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
          margin: 14px 0px 0px 0px;
        }
      }
    }
  }
  .desktop-none{
    display: none;
  }  
}
@media (max-width: 414px) {
  .card{
    display: flex;
    width: 174px;
    height: 222px;
    margin: 0px 0px 0px 17px;
    background: #FFFFFF;
    box-shadow: 0px 5px 18px rgba(0, 0, 0, 0.1);
    border-radius: 9px;
    &__container{
      display: flex;
      flex-direction: column;
      margin: 10px 0px 0px 0px;
      &__image{
        display: none;
      }
      &__right{
        display: flex;
        flex-direction: row;
        margin: 5px 0px 0px 5px;
        &__title{
          display: none;
        }
        &__star{
          display: flex;
          margin: 7px 0px 0px 0px;
          width: 10px;
          height: 9px;
          img{
            margin: 0px 0px 0px 1px;
          }
        }
        &__price{
          display: flex;
          font-family: Roboto;
          font-style: normal;
          font-weight: bold;
          font-size: 18px;
          line-height: 21px;
          color: #8B75C8;
          margin: 0px 0px 0px 80px;
        }
      }
    }
  }
  .mob-image{
    display: flex;
    margin: 0px 0px 0px 10px;
    &__prod{
      display: flex;
      margin: 0px 0px 0px 0px;
    }
    &__plus{
      display: flex;
      width: 25px;
      height: 25px;
      margin: 0px 0px 0px 0px;
      background: #EEEEEE;
      border-radius: 22px;
      img{
        margin: 0px 0px 0px 4px;
      }
    }
  }
  .mob-title{
    margin: 0px 0px 0px 10px;
    display: flex;
    font-family: Roboto;
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 16px;
    color: #353535;
  }
}
@media (max-width: 375px) {
  .card{
    display: flex;
    width: 174px;
    height: 222px;
    margin: 0px 0px 0px 8px;
    background: #FFFFFF;
    box-shadow: 0px 5px 18px rgba(0, 0, 0, 0.1);
    border-radius: 9px;
    &__container{
      display: flex;
      flex-direction: column;
      margin: 10px 0px 0px 0px;
      &__image{
        display: none;
      }
      &__right{
        display: flex;
        flex-direction: row;
        margin: 5px 0px 0px 5px;
        &__title{
          display: none;
        }
        &__star{
          display: flex;
          margin: 5px 0px 0px 3px;
          width: 13px;
          height: 11px;
          img{
            margin: 0px 0px 0px 0px;
          }
        }
        &__price{
          display: flex;
          font-family: Roboto;
          font-style: normal;
          font-weight: bold;
          font-size: 18px;
          line-height: 21px;
          color: #8B75C8;
          margin: -1px 0px 0px 80px;
        }
      }
    }
  }
  .mob-image{
    display: flex;
    margin: 2px 0px 0px 20px;
    &__prod{
      display: flex;
      margin: 0px 0px 0px 0px;
    }
    &__plus{
      display: flex;
      width: 25px;
      height: 25px;
      margin: -3px 0px 0px -7px;
      background: #EEEEEE;
      border-radius: 22px;
      img{
        margin: 0px 0px 0px 3px;
      }
    }
  }
  .mob-title{
    margin: 7px 0px 0px 12px;
    display: flex;
    font-family: Roboto;
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 16px;
    color: #353535;
  }
}
</style>