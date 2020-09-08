<template>
  <div class="top">
      <div class="top__container">
        <div class="top__container__title">
            <BlockTopTitleSubtitle/>
        </div>
        <div>
            <BlockProductTop class="top__container__blocks" :content="data.top"/>
        </div>
        <div class="top__container__button">
            <BlockButtonAllModels/>
        </div>
        <div class="scroll-mob">
          <img src="@/components/blocks/scroll/Vector.svg" />
      </div>
      </div>
  </div>
</template>

<script>

import BlockTopTitleSubtitle from "@/components/blocks/BlockTopTitleSubtitle"
import BlockProductTop from "@/components/blocks/BlockProductTop"
import BlockButtonAllModels from "@/components/blocks/BlockButtonAllModels"

export default {
    components: {
        BlockTopTitleSubtitle,
        BlockButtonAllModels,
        BlockProductTop 
    },
        data() {
        return{
            data: {
                top: {
                    items: [
                        {
                            image: '',
                            title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                            titleMob: 'Наушники Bluetooth Baseus',
                            price: '1 950 ₽'
                        },
                        {
                            image: '',
                            title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                            titleMob: 'Наушники Bluetooth Baseus',
                            price: '1 950 ₽'
                        },
                        {
                            image: '',
                            title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                            titleMob: 'Наушники Bluetooth Baseus',
                            price: '1 950 ₽'
                        },
                        {
                            image: '',
                            title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                            titleMob: 'Наушники Bluetooth Baseus',
                            price: '1 950 ₽'
                        },
                        {
                            image: '',
                            title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                            titleMob: 'Наушники Bluetooth Baseus',
                            price: '1 950 ₽'
                        },
                        {
                            image: '',
                            title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                            titleMob: 'Наушники Bluetooth Baseus',
                            price: '1 950 ₽'
                        },
                        {
                            image: '',
                            title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                            titleMob: 'Наушники Bluetooth Baseus',
                            price: '1 950 ₽'
                        },
                        {
                            image: '',
                            title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                            titleMob: 'Наушники Bluetooth Baseus',
                            price: '1 950 ₽'
                        },
                        {
                            image: '',
                            title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                            titleMob: 'Наушники Bluetooth Baseus',
                            price: '1 950 ₽'
                        }
                    ]
                }
            }
        }
    }
}

</script>

<style lang="scss" scoped>
    .top{
        height: 1008px;
        background: #E6E1F2;
        display: flex;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 0px 340px 0px 343px;
            &__title{
                display: flex;
                margin: 0px 0px 0px 108px;
            }
            &__blocks{
                display: flex;
                flex-wrap: wrap;    
                height: 100%;
                width: 1300px;
                margin: -4px 0px 0px -2px;
            }
            &__button{
                display: flex;
                margin: 60px 0px 0px 440px;
            }
        }
    }
    .scroll-mob{
        display: none;
    }
   @media (max-width: 1584px) {
    .top{
        height: 1008px;
        background: #E6E1F2;
        display: flex;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 0px 340px 0px 100px;
            &__title{
                display: flex;
                margin: 0px 0px 0px 107px;
            }
            &__blocks{
                display: flex;
                flex-wrap: wrap;    
                height: 100%;
                width: 1300px;
                margin: -2px 0px 0px 0px;
            }
            &__button{
                display: flex;
                margin: 60px 0px 0px 440px;
            }
        }
    }
    .scroll-mob{
        display: none;
    }
   }
   @media (max-width: 1440px) {
    .top{
        height: 1008px;
        background: #E6E1F2;
        display: flex;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 0px 340px 0px 20px;
            &__title{
                display: flex;
                margin: 0px 0px 0px 107px;
            }
            &__blocks{
                display: flex;
                flex-wrap: wrap;    
                height: 100%;
                width: 1300px;
                margin: -2px 0px 0px 0px;
            }
            &__button{
                display: flex;
                margin: 60px 0px 0px 440px;
            }
        }
    }
    .scroll-mob{
        display: none;
    }
   }
   @media (max-width: 1255px) {
    .top{
        height: 1308px;
        background: #E6E1F2;
        display: flex;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 0px 340px 0px 20px;
            &__title{
                display: flex;
                margin: 0px 0px 0px 107px;
            }
            &__blocks{
                display: flex;
                flex-wrap: wrap;    
                height: 100%;
                width: 900px;
                margin: -2px 0px 0px 100px;
            }
            &__button{
                display: flex;
                margin: 30px 0px 0px 440px;
            }
        }
    }
    .scroll-mob{
        display: none;
    }
   }
   @media (max-width: 768px) {
    .top{
        height: 1308px;
        background: #E6E1F2;
        display: flex;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 0px 340px 0px -90px;
            &__title{
                display: flex;
                margin: 0px 0px 0px 207px;
            }
            &__blocks{
                display: flex;
                flex-wrap: wrap;    
                height: 100%;
                width: 900px;
                margin: -2px 0px 0px 150px;
            }
            &__button{
                display: flex;
                margin: 30px 0px 0px 280px;
            }
        }
    }
    .scroll-mob{
        display: none;
    }
   }
@media (max-width: 414px) {
    .top{
        height: 499px;
        background: #F8F5FE;
        display: flex;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 0px 0px 0px 0px;
            &__title{
                display: flex;
                margin: 50px 0px 0px 50px;
            }
            &__blocks{
                display: flex;
                flex-flow: column wrap;        
                height: 230px;
                width: 400px;
                margin: 0px 0px 0px 0px;
                overflow-x: auto;
            }
            &__button{
                display: none;
            }
        }
    }
    .scroll-mob{
        display: flex;
        margin: 18px 0px 0px 170px;
        height: 39px;
        width: 39px;
        background: #FFFFFF;
        box-shadow: 0px 5.81081px 15.1081px rgba(140, 121, 199, 0.3);
        border-radius: 25.5676px;
        img{
            display: flex;
            margin: 0px 0px 0px 10px;
        }
    } 
}
@media (max-width: 375px) {
    .top{
        height: 495px;
        background: #F8F5FE;
        display: flex;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 0px 0px 0px 0px;
            &__title{
                display: flex;
                margin: 52px 0px 0px 22px;
            }
            &__blocks{
                display: flex;
                flex-flow: column wrap;        
                height: 230px;
                width: 400px;
                margin: -20px 0px 0px -5px;
                overflow-x: auto;
            }
            &__button{
                display: none;
            }
        }
    }
    .scroll-mob{
        display: flex;
        margin: 12px 0px 0px 172px;
        height: 39px;
        width: 39px;
        background: #FFFFFF;
        box-shadow: 0px 5.81081px 15.1081px rgba(140, 121, 199, 0.3);
        border-radius: 25.5676px;
        img{
            display: flex;
            margin: 0px 0px 0px 10px;
        }
    } 
}
</style>