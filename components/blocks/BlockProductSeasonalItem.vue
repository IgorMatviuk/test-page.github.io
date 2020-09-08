<template>
  <div class="card">
    <div class="card__container">
      <div class="card__container__sale-image">
        <div class="card__container__sale-image__image">
          <img src="@/components/blocks/Seasonal/besprovodnye.png" width="218px" />
        </div>
        <div class="image-mob">
          <img src="@/components/blocks/Seasonal/besprovodnye-mob.png" width="218px" />
        </div>       
        <div class="card__container__sale-image__sale">
          <p>{{ content.sale }}</p>
        </div>
      </div>
      <div class="card__container__title">
        <p>{{ content.title }}</p>
      </div>
      <div class="title-mob">
        <p>{{ content.titleMob }}</p>
      </div>
      <div class="card-line"></div>
      <div class="card__container__days-block">
        <div class="card__container__days-block__days">
          <p>{{ content.numberDays}}</p>
          <p><a>Дней</a></p>
        </div>
        <div class="number-days-mob" >
          <div>
          <p>{{ content.numberDaysMob}}</p>
          <p><a>Дней</a></p>
          </div>
        </div>
        <div class="card__container__days-block__text">{{ content.days}}</div>
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
    width: 270px;
    height: 378px;
    background: #FFFFFF;
    box-shadow: 0px 0px 18px rgba(0, 0, 0, 0.1);
    border-radius: 9.5px;
    margin: 0px 0px 0px 0px;
    &__container{
      display: flex;
      flex-direction: column;
      margin: 0px 15px 0px 15px;
      &__sale-image{
        display: flex;
        &__image{
          width: 218px;
          margin: 32px 0px 0px 14px;
        }
        &__sale{
          display: flex;
          position: absolute;
          z-index: 2;
          margin: 10px 0px 0px 206px;
          width: 40px;
          height: 40px;
          background: #97D513;
          border-radius: 70px;
          font-family: Roboto;
          font-style: normal;
          font-weight: bold;
          font-size: 13px;
          line-height: 15px;
          text-align: center;
          align-items: center;
          color: #FFFFFF;
          p{
            display: flex;
            margin: 0px 0px 0px 8px;
          }
        }
      }
    &__title{
      display: flex;
      width: 246px;
      margin: 15px 0px 0px 1px;
      font-family: Roboto;
      font-style: normal;
      font-weight: 700;
      font-size: 14px;
      line-height: 20px;
      color: #353535;
    }
    &__days-block{
      display: flex;
      flex-direction: row;
      width: 100%;
      &__days{
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 28px 0px 0px 0px;
        width: 54px;
        height: 54px;
        background: #8B75C8;
        border-radius: 50%;
        p{
          margin: 8px 0px 0px 0px;
          display: flex;
          font-family: Roboto;
          font-style: normal;
          font-weight: bold;
          font-size: 22.7812px;
          line-height: 27px;
          text-align: center;
          color: #FFFFFF;
          text-shadow: 0px 0px 24.3px rgba(0, 0, 0, 0.25);
          a{
            margin: -10px 0px 0px 0px;
            font-family: Roboto;
            font-style: normal;
            font-weight: normal;
            font-size: 10.2516px;
            line-height: 12px;
            text-align: center;
            color: #FFFFFF;
            text-shadow: 0px 0px 24.3px rgba(0, 0, 0, 0.25);
          }
        }
      }
      &__text{
        margin: 25px 0px 0px 20px;
        width: 120px;
        display: flex;
        align-items: center;
        text-align: start;
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 12px;
        line-height: 14px;
        display: flex;
        color: #4B4B4B;
      }
    }
  }
}
.number-days-mob{
  div{
    display: none;
  }
}
.image-mob{
  display: none;
}
.title-mob{
  display: none;
}
.card-line{
  display: none;
}
.display-none{
  display: none;
}
@media (max-width: 414px) {
  .card{
    display: flex;
    width: 174px;
    height: 285px;
    background: #FFFFFF;
    box-shadow: 0px 0px 18px rgba(0, 0, 0, 0.1);
    border-radius: 9.5px;
    margin: 0px 0px 0px 30px;
    &__container{
      display: flex;
      flex-direction: column;
      margin: 0px 5px 0px 5px;
      &__sale-image{
        display: flex;
        flex-direction: column-reverse;
        margin: 0px 0px 0px 0px;
        &__image{
          display: none;
        }
        &__sale{
          display: flex;
          position: relative;
          margin: 4px 0px 0px 120px;
          width: 28px;
          height: 28px;
          background: #97D513;
          border-radius: 70px;
          font-family: Roboto;
          font-style: normal;
          font-weight: bold;
          font-size: 9.1px;
          line-height: 11px;
          display: flex;
          align-items: center;
          text-align: center;
          color: #FFFFFF;
          p{
            display: flex;
            margin: 0px 0px 0px 5px;
          }
        }
      }
    &__title{
      display: none;
    }
    &__days-block{
      display: flex;
      flex-direction: row;
      width: 100%;
      &__days{
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 10px 0px 0px 0px;
        width: 54px;
        height: 54px;
        background: #8B75C8;
        border-radius: 50%;
        p{
          margin: 8px 0px 0px 0px;
          display: flex;
          font-family: Roboto;
          font-style: normal;
          font-weight: bold;
          font-size: 22.7812px;
          line-height: 27px;
          text-align: center;
          color: #FFFFFF;
          text-shadow: 0px 0px 24.3px rgba(0, 0, 0, 0.25);
          a{
            margin: -10px 0px 0px 0px;
            font-family: Roboto;
            font-style: normal;
            font-weight: normal;
            font-size: 10.2516px;
            line-height: 12px;
            text-align: center;
            color: #FFFFFF;
            text-shadow: 0px 0px 24.3px rgba(0, 0, 0, 0.25);
          }
        }
      }
      &__text{
        margin: 25px 0px 0px 5px;
        width: 105px;
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 11px;
        line-height: 13px;
        display: flex;
        align-items: center;
        color: #4B4B4B;
      }
    }
  }
} 
.image-mob{
  margin: 0px 0px 0px 0px;
  display: flex;
  width: 150px;
  height: 132;
} 
.title-mob{
  margin: 0px 0px 0px 0px;
  display: flex;
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 20px;
  color: #353535;
  width: 141px;
} 
}
@media (max-width: 375px) {
  .card{
    display: flex;
    width: 174px;
    height: 285px;
    background: #FFFFFF;
    box-shadow: 0px 0px 18px rgba(0, 0, 0, 0.1);
    border-radius: 9.5px;
    margin: 0px 0px 0px 10px;
    &__container{
      display: flex;
      flex-direction: column;
      margin: 0px 5px 0px 5px;
      &__sale-image{
        display: flex;
        flex-direction: column-reverse;
        margin: 3px 0px 0px 0px;
        &__image{
          display: none;
        }
        &__sale{
          display: flex;
          position: relative;
          z-index: 3;
          margin: 5px 0px 0px 133px;
          width: 28px;
          height: 28px;
          background: #97D513;
          border-radius: 70px;
          font-family: Roboto;
          font-style: normal;
          font-weight: bold;
          font-size: 9.1px;
          line-height: 11px;
          display: flex;
          align-items: center;
          text-align: center;
          color: #FFFFFF;
          p{
            display: flex;
            margin: 0px 0px 0px 5px;
          }
        }
      }
    &__title{
      display: none;
    }
    &__days-block{
      display: flex;
      flex-direction: row;
      width: 100%;
      &__days{
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 11px 0px 0px 10px;
        width: 54px;
        height: 54px;
        background: #8B75C8;
        border-radius: 50%;
        p{
          display: none;
          a{
            margin: -10px 0px 0px 0px;
            font-family: Roboto;
            font-style: normal;
            font-weight: normal;
            font-size: 10.2516px;
            line-height: 12px;
            text-align: center;
            color: #FFFFFF;
            text-shadow: 0px 0px 24.3px rgba(0, 0, 0, 0.25);
          }
        }
      }
      &__text{
        margin: 15px 0px 0px 10px;
        width: 90px;
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 11px;
        line-height: 13px;
        display: flex;
        align-items: center;
        color: #4B4B4B;
      }
    }
  }
} 
.image-mob{
  margin: -25px 0px 0px 10px;
  display: flex;
  z-index: 2;
  img{
    width: 150px;
    height: 132px;
  }
} 
.title-mob{
  margin: 14px 0px 0px 10px;
  display: flex;
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 20px;
  color: #353535;
  width: 141px;
} 
.card-line{
    display: flex;
    border: 1px solid #EBEBEB;
    width: 174px;
    height: 1px;
    margin: 9px 0px 0px -5px;
}
.number-days-mob{
  div{
    display: flex;
    flex-direction: column;
    p{
            margin: 20px 0px 0px -39px;
            display: flex;
            font-family: Roboto;
            font-style: normal;
            font-weight: bold;
            font-size: 22.7812px;
            line-height: 27px;
            text-align: center;
            color: #FFFFFF;
            text-shadow: 0px 0px 24.3px rgba(0, 0, 0, 0.25);
              a{
              margin: -23px 0px 0px 0px;
              font-family: Roboto;
              font-style: normal;
              font-weight: normal;
              font-size: 10.2516px;
              line-height: 12px;
              text-align: center;
              color: #FFFFFF;
              text-shadow: 0px 0px 24.3px rgba(0, 0, 0, 0.25);
            }
    }
  }
}
}
</style>