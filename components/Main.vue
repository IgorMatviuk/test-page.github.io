<template>
  <div class="main">
    <div class="main__container">
      <div class="main__container__image main__container__image-mob">
        <div> 
          <img class="display-none" src="../assets/image/Main/Rectangle 173.svg" />
        </div>
      </div>
      <div class="main__container__title-button">
          <div class="main__container__title-button__title">
            <p>Bestseller</p>
            </div>
          <div class="main__container__title-button__button">
            <button>Купить</button>
        </div>
        <div class="main__container__title-button__group main__container__title-button__group-mob">
          <img class="display-none414" src="../assets/image/Main/Group 264.svg" />
        </div>
      </div>
      <div class="main__container__headphones main__container__headphones-mob">
        <img class="display-none" src="../assets/image/Main/NA 1.svg" />
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
    .main{
      display: flex;
      height: 706px;
      background-color: #8B75C8;
        &__container{
          display: flex;
          position: relative;
          align-items: center;
          &__image{
              padding: 27px 0px 0px 665px;
              display: flex;
              position: absolute;
              z-index: 1px;
          }
          &__title-button{
            display: flex;
            flex-direction: column;
            align-items: center;
            position: absolute;
            margin: 225px 0px 0px 395px;
            z-index: 2px;
            &__title{
              display: flex;
              margin: 8px 0px 0px 0px;
              font-family: Roboto;
              font-style: normal;
              font-weight: bold;
              font-size: 192px;
              line-height: 225px;
              text-align: center;
              text-transform: uppercase;
              color: #FFFFFF;
            }
            &__button{
              margin: 77px 0px 0px 0px;
              button{
              display: flex;
              justify-content: center;
              align-items: center;
              height: 60px;
              width: 253px;
              background: transparent;
              border: 1px solid #FFFFFF;
              box-sizing: border-box;
              border-radius: 220px;
              font-family: Roboto;
              font-style: normal;
              font-weight: bold;
              font-size: 13px;
              line-height: 15px;
              text-align: center;
              color: #FFFFFF;
              }
            }
            &__group{
              margin: 53px 0px 0px 0px;
            }
        }
        &__headphones{
          display: flex;
          align-items: center;
          position: absolute;
          z-index: 3px;
          padding: 0px 0px 34px 695px;
        }
      }
    }
@media (max-width: 1580px) {
    .main{
      display: flex;
      height: 706px;
      background-color: #8B75C8;
        &__container{
          display: flex;
          position: relative;
          align-items: center;
          &__image{
              padding: 27px 0px 0px 450px;
              display: flex;
              position: absolute;
              z-index: 1px;
          }
          &__title-button{
            display: flex;
            flex-direction: column;
            align-items: center;
            position: absolute;
            margin: 170px 0px 0px 195px;
            z-index: 2px;
            &__title{
              margin: 0px 0px 0px 0px;
              display: flex;
              font-family: Roboto;
              font-style: normal;
              font-weight: bold;
              font-size: 192px;
              line-height: 225px;
              text-align: center;
              text-transform: uppercase;
              color: #FFFFFF;
            }
            &__button{
              padding: 40px 0px 0px 18px;
              button{
              display: flex;
              justify-content: center;
              align-items: center;
              height: 60px;
              width: 253px;
              background: transparent;
              border: 1px solid #FFFFFF;
              box-sizing: border-box;
              border-radius: 220px;
              font-family: Roboto;
              font-style: normal;
              font-weight: bold;
              font-size: 13px;
              line-height: 15px;
              text-align: center;
              color: #FFFFFF;
              }
            }
            &__group{
              padding: 10px 0px 0px 16px;
            }
        }
        &__headphones{
          display: flex;
          align-items: center;
          position: absolute;
          z-index: 3px;
          padding: 0px 0px 34px 495px;
        }
      }
    }
}
@media (max-width: 1360px) {
    .main{
      display: flex;
      height: 706px;
      background-color: #8B75C8;
        &__container{
          display: flex;
          position: relative;
          align-items: center;
          &__image{
              padding: 27px 0px 0px 370px;
              display: flex;
              position: absolute;
              z-index: 1px;
          }
          &__title-button{
            display: flex;
            flex-direction: column;
            align-items: center;
            position: absolute;
            margin: 170px 0px 0px 105px;
            z-index: 2px;
            &__title{
              display: flex;
              font-family: Roboto;
              font-style: normal;
              font-weight: bold;
              font-size: 192px;
              line-height: 225px;
              text-align: center;
              text-transform: uppercase;
              color: #FFFFFF;
            }
            &__button{
              padding: 44px 0px 0px 18px;
              button{
              display: flex;
              justify-content: center;
              align-items: center;
              height: 60px;
              width: 253px;
              background: transparent;
              border: 1px solid #FFFFFF;
              box-sizing: border-box;
              border-radius: 220px;
              font-family: Roboto;
              font-style: normal;
              font-weight: bold;
              font-size: 13px;
              line-height: 15px;
              text-align: center;
              color: #FFFFFF;
              }
            }
            &__group{
              padding: 0px 0px 0px 16px;
            }
        }
        &__headphones{
          display: flex;
          align-items: center;
          position: absolute;
          z-index: 3px;
          padding: 0px 0px 34px 405px;
        }
      }
    }
}
@media (max-width: 1224px) {
    .main{
      display: flex;
      height: 706px;
      background-color: #8B75C8;
        &__container{
          display: flex;
          position: relative;
          align-items: center;
          &__image{
              padding: 27px 0px 0px 270px;
              display: flex;
              position: absolute;
              z-index: 1px;
          }
          &__title-button{
            display: flex;
            flex-direction: column;
            align-items: center;
            position: absolute;
            margin: 190px 0px 0px 25px;
            z-index: 2px;
            &__title{
              display: flex;
              font-family: Roboto;
              font-style: normal;
              font-weight: bold;
              font-size: 192px;
              line-height: 225px;
              text-align: center;
              text-transform: uppercase;
              color: #FFFFFF;
            }
            &__button{
              padding: 44px 0px 0px 18px;
              button{
              display: flex;
              justify-content: center;
              align-items: center;
              height: 60px;
              width: 253px;
              background: transparent;
              border: 1px solid #FFFFFF;
              box-sizing: border-box;
              border-radius: 220px;
              font-family: Roboto;
              font-style: normal;
              font-weight: bold;
              font-size: 13px;
              line-height: 15px;
              text-align: center;
              color: #FFFFFF;
              }
            }
            &__group{
              padding: 0px 0px 0px 16px;
            }
        }
        &__headphones{
          display: flex;
          align-items: center;
          position: absolute;
          z-index: 3px;
          padding: 0px 0px 34px 290px;
        }
      }
    }
}
@media (max-width: 1024px) {
    .main{
      display: flex;
      height: 706px;
      background-color: #8B75C8;
        &__container{
          display: flex;
          position: relative;
          align-items: center;
          &__image{
              padding: 27px 0px 0px 170px;
              display: flex;
              position: absolute;
              z-index: 1px;
          }
          &__title-button{
            display: flex;
            flex-direction: column;
            align-items: center;
            position: absolute;
            margin: 170px 0px 0px 40px;
            z-index: 2px;
            &__title{
              display: flex;
              font-family: Roboto;
              font-style: normal;
              font-weight: bold;
              font-size: 142px;
              line-height: 225px;
              text-align: center;
              text-transform: uppercase;
              color: #FFFFFF;
            }
            &__button{
              padding: 44px 0px 0px 18px;
              button{
              display: flex;
              justify-content: center;
              align-items: center;
              height: 60px;
              width: 253px;
              background: transparent;
              border: 1px solid #FFFFFF;
              box-sizing: border-box;
              border-radius: 220px;
              font-family: Roboto;
              font-style: normal;
              font-weight: bold;
              font-size: 13px;
              line-height: 15px;
              text-align: center;
              color: #FFFFFF;
              }
            }
            &__group{
              padding: 0px 0px 0px 16px;
            }
        }
        &__headphones{
          display: flex;
          align-items: center;
          position: absolute;
          z-index: 3px;
          padding: 0px 0px 34px 210px;
        }
      }
    } 
}
@media (max-width: 768px) {
    .main{
      display: flex;
      height: 706px;
      background-color: #8B75C8;
        &__container{
          display: flex;
          position: relative;
          align-items: center;
          &__image{
              padding: 27px 0px 0px 70px;
              display: flex;
              position: absolute;
              z-index: 1px;
          }
          &__title-button{
            display: flex;
            flex-direction: column;
            align-items: center;
            position: absolute;
            margin: 190px 0px 0px 0px;
            z-index: 2px;
            &__title{
              font-size: 120px;
              margin-left: 30px;
            }
            &__button{
              padding: 34px 0px 0px 18px;
            }
            &__group{
              padding: 0px 0px 0px 16px;
            }
        }
        &__headphones{
          display: flex;
          align-items: center;
          position: absolute;
          z-index: 3px;
          padding: 0px 0px 34px 100px;
        }
      }
    }   
}
@media (max-width: 414px) {
    .main{
      display: flex;
      height: 450px;
      background-color: #8B75C8;
        &__container{
          display: flex;
          position: relative;
          align-items: center;
          &__image{
              padding: 27px 0px 0px 70px;
              display: flex;
              position: absolute;
              z-index: 1px;
          }
          &__image-mob{
              display: flex;
              position: absolute;
              z-index: 1px;
              background-image: url("../assets/image/Main/Rectangle 179mob.svg");
              background-repeat: no-repeat;
              width: 350px;
              height: 350px;
              left: 60px;
              top: 100px;
          }
          &__title-button{
            display: flex;
            flex-direction: column;
            align-items: center;
            position: absolute;
            margin: 0px 0px 0px 45px;
            z-index: 2px;
            &__title{
              font-size: 48px;
              margin: 0px 0px 0px 30px;
              p{
                margin: 60px 0px 0px 0px;
              }
            }
            &__button{
              margin: 0px 0px 0px 18px;
            }
            &__group{
              margin: 0px 0px 0px 16px;
            }
        }
        &__headphones{
          display: flex;
          align-items: center;
          position: absolute;
          z-index: 3px;
          padding: 0px 0px 34px 100px;
        }
        &__headphones-mob{
            display: flex;
            position: absolute;
            z-index: 1px;
            background-image: url("../assets/image/Main/NA 2.svg");
            background-repeat: no-repeat;
            width: 350px;
            height: 350px;
            left: 135px;
            bottom: -60px;
        }
      }
    }   
  .display-none{
    display: none;
  }
}
@media (max-width: 414px) {
    .main{
      display: flex;
      height: 420px;
      background-color: #8B75C8;
        &__container{
          display: flex;
          position: relative;
          align-items: center;
          &__image{
              padding: 27px 0px 0px 70px;
              display: flex;
              position: absolute;
              z-index: 1px;
          }
          &__image-mob{
              display: flex;
              position: absolute;
              z-index: 1px;
              background-image: url("../assets/image/Main/Rectangle 179mob.svg");
              background-repeat: no-repeat;
              width: 350px;
              height: 350px;
              left: 35px;
              top: 85px;
          }
          &__title-button{
            display: flex;
            flex-direction: column;
            align-items: center;
            position: absolute;
            margin: 0px 0px 14px 16px;
            z-index: 2px;
            &__title{
              font-size: 48px;
              margin-left: 0px 0px 0px 10px;
              p{
                margin: 60px 0px 0px 0px;
              }
            }
            &__button{
              padding: 0px 0px 0px 34px;
              z-index: 2;
              position: absolute;
              top: 247px;
              button{
                width: 230px;
                height: 51px;
                font-size: 12px;
                line-height: 14px;
                font-weight: 300;
              }

            }
            &__group{
              padding: 25px 0px 0px 16px;
            }
            &__group-mob{
              padding: 25px 0px 0px 16px;
              display: flex;
              position: absolute;
              z-index: 1px;
              background-image: url("../assets/image/Main/Group 274mob.svg");
              background-repeat: no-repeat;
              top: 335px;
              left: 160px;
              width: 50px;
              height: 50px;
            }
        }
        &__headphones{
          display: flex;
          align-items: center;
          position: absolute;
          z-index: 3px;
          padding: 0px 0px 34px 100px;
        }
        &__headphones-mob{
            display: flex;
            position: absolute;
            z-index: 1px;
            background-image: url("../assets/image/Main/NA 2.svg");
            background-repeat: no-repeat;
            width: 350px;
            height: 350px;
            left: 105px;
            bottom: -102px;
        }
      }
    }   
  .display-none414{
    display: none;
  }
}
@media (max-width: 414px) {
    .main{
      display: flex;
      height: 420px;
      background-color: #8B75C8;
        &__container{
          display: flex;
          position: relative;
          align-items: center;
          &__image{
              padding: 27px 0px 0px 70px;
              display: flex;
              position: absolute;
              z-index: 1px;
          }
          &__image-mob{
              display: flex;
              position: absolute;
              z-index: 1px;
              background-image: url("../assets/image/Main/Rectangle 179mob.svg");
              background-repeat: no-repeat;
              width: 350px;
              height: 350px;
              left: 35px;
              top: 85px;
          }
          &__title-button{
            display: flex;
            flex-direction: column;
            align-items: center;
            position: absolute;
            margin: 0px 0px 14px 16px;
            z-index: 2px;
            &__title{
              font-size: 48px;
              margin-left: 0px 0px 0px 10px;
              p{
                margin: 60px 0px 0px 0px;
              }
            }
            &__button{
              padding: 0px 0px 0px 34px;
              z-index: 2;
              position: absolute;
              top: 247px;
              button{
                width: 230px;
                height: 51px;
                font-size: 12px;
                line-height: 14px;
                font-weight: 300;
              }

            }
            &__group{
              padding: 25px 0px 0px 16px;
            }
            &__group-mob{
              padding: 25px 0px 0px 16px;
              display: flex;
              position: absolute;
              z-index: 1px;
              background-image: url("../assets/image/Main/Group 274mob.svg");
              background-repeat: no-repeat;
              top: 335px;
              left: 160px;
              width: 50px;
              height: 50px;
            }
        }
        &__headphones{
          display: flex;
          align-items: center;
          position: absolute;
          z-index: 3px;
          padding: 0px 0px 34px 100px;
        }
        &__headphones-mob{
            display: flex;
            position: absolute;
            z-index: 1px;
            background-image: url("../assets/image/Main/NA 2.svg");
            background-repeat: no-repeat;
            width: 350px;
            height: 350px;
            left: 105px;
            bottom: -102px;
        }
      }
    }   
  .display-none414{
    display: none;
  }
}
@media (max-width: 375px) {
    .main{
      display: flex;
      height: 420px;
      background-color: #8B75C8;
        &__container{
          display: flex;
          position: relative;
          align-items: center;
          &__image{
              padding: 27px 0px 0px 70px;
              display: flex;
              position: absolute;
              z-index: 1px;
          }
          &__image-mob{
              display: flex;
              position: absolute;
              z-index: 1px;
              background-image: url("../assets/image/Main/Rectangle 179mob.svg");
              background-repeat: no-repeat;
              width: 350px;
              height: 350px;
              left: 35px;
              top: 85px;
          }
          &__title-button{
            display: flex;
            flex-direction: column;
            align-items: center;
            position: absolute;
            margin: 0px 0px 14px 16px;
            z-index: 2px;
            &__title{
              font-size: 48px;
              margin: -2px 0px 0px 30px;
              p{
                margin: 60px 0px 0px 0px;
              }
            }
            &__button{
              margin: -2px 0px 0px 0px;
              z-index: 2;
              position: absolute;
              top: 247px;
              button{
                width: 230px;
                height: 51px;
                font-size: 12px;
                line-height: 14px;
                font-weight: 300;
              }

            }
            &__group{
              padding: 25px 0px 0px 16px;
            }
            &__group-mob{
              margin: -2px 0px 0px 0px;
              display: flex;
              position: absolute;
              z-index: 1px;
              background-image: url("../assets/image/Main/Group 274mob.svg");
              background-repeat: no-repeat;
              top: 335px;
              left: 160px;
              width: 50px;
              height: 50px;
            }
        }
        &__headphones{
          display: flex;
          align-items: center;
          position: absolute;
          z-index: 3px;
          padding: 0px 0px 34px 100px;
        }
        &__headphones-mob{
            display: flex;
            position: absolute;
            z-index: 1px;
            background-image: url("../assets/image/Main/NA 2.svg");
            background-repeat: no-repeat;
            width: 350px;
            height: 350px;
            left: 105px;
            bottom: -102px;
        }
      }
    }   
  .display-none414{
    display: none;
  }
}
</style>