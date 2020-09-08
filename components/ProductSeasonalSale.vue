<template>
  <div class="seasonal">
      <div class="seasonal__title">
          <BlockSaleTitleSubtitle/>
      </div>
        <div class="container-product">
            <BlockProductSeasonal class="seasonal__cards" :content="data.headphonesSeasonal"/>
        </div>
        <div class="scroll-mob">
          <img src="@/components/blocks/scroll/Vector.svg" />
        </div>
        <div class="seasonal__button">
            <BlockButtonAllModels/>
        </div>
  </div>
</template>

<script>

import BlockSaleTitleSubtitle from "@/components/blocks/BlockSaleTitleSubtitle"
import BlockProductSeasonal from "@/components/blocks/BlockProductSeasonal"
import BlockButtonAllModels from "@/components/blocks/BlockButtonAllModels"

export default {
    components:{
        BlockSaleTitleSubtitle,
        BlockProductSeasonal,
        BlockButtonAllModels
    },
    data() {
    return{
        data: {
            headphonesSeasonal: {
                items: [
                    {
                        sale: '-15%',
                        title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                        titleMob: 'Наушники Bluetooth Baseus Encok',
                        image: '',
                        days: 'До конца акции на этот товар осталось:',
                        numberDays: '50',
                        numberDaysMob: '06'
                    },
                                        {
                        sale: '-5%',
                        title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                        titleMob: 'Наушники Bluetooth Baseus Encok',
                        image: '',
                        days: 'До конца акции на этот товар осталось:',
                        numberDays: '50',
                        numberDaysMob: '03'
                    },
                                        {
                        sale: '-20%',
                        title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                        titleMob: 'Наушники Bluetooth Baseus Encok',
                        image: '',
                        days: 'До конца акции на этот товар осталось:',
                        numberDays: '50',
                        numberDaysMob: '04'
                    },
                                        {
                        sale: '-15%',
                        title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                        titleMob: 'Наушники Bluetooth Baseus Encok',
                        image: '',
                        days: 'До конца акции на этот товар осталось:',
                        numberDays: '50',
                        numberDaysMob: '07'
                    }
                ]
            }
        }
    }
}
}
</script>

<style lang="scss" scoped>
    .seasonal{
        display: flex;
        flex-direction: column;
        background: #FFFFFF;
        height: 845px;
        &__title{
            display: flex;
            margin: -9px 0px 0px 710px;
        }
        &__cards{
            display: flex;
            justify-content: space-between;
            width: 100%;
            margin: 18px 0px 0px 7px;
        }
        &__button{
            display: flex;
            margin: 50px 0px 0px 790px;
        }
    }
    .scroll-mob{
        display: none;
    }
@media (max-width: 1320px) {
    .seasonal{
        display: flex;
        flex-direction: column;
        background: #FFFFFF;
        height: 845px;
        &__title{
            display: flex;
            margin: -8px 0px 0px 400px;
        }
        &__cards{
            display: flex;
            justify-content: space-between;
            width: 100%;
            margin: 18px 0px 0px 7px;
        }
        &__button{
            display: flex;
            margin: 50px 0px 0px 450px;
        }
    }
    .scroll-mob{
        display: none;
    }
}
@media (max-width: 1120px) {
    .seasonal{
        display: flex;
        flex-direction: column;
        background: #FFFFFF;
        height: 1145px;
        &__title{
            display: flex;
            margin: -20px 0px 0px 340px;
        }
        &__cards{
            display: flex;
            flex-flow: column wrap;
            height: 780px;
            width: 60%;
            margin: 5px 0px 0px 300px;
        }
        &__button{
            display: flex;
            margin: 40px 0px 0px 450px;
        }
    }
    .scroll-mob{
        display: none;
    }
}
@media (max-width: 1024px) {
    .seasonal{
        display: flex;
        flex-direction: column;
        background: #FFFFFF;
        height: 1145px;
        &__title{
            display: flex;
            margin: -20px 0px 0px 180px;
        }
        &__cards{
            display: flex;
            flex-flow: column wrap;
            height: 780px;
            width: 60%;
            margin: 5px 0px 0px 150px;
        }
        &__button{
            display: flex;
            margin: 40px 0px 0px 250px;
        }
    }
    .scroll-mob{
        display: none;
    }
}
@media (max-width: 414px) {
    .seasonal{
        display: flex;
        flex-direction: column;
        background: #FFFFFF;
        height: 668px;
        &__title{
            display: flex;
            margin: 35px 0px 0px 50px;
        }
        &__cards{
            display: flex;
            margin: 0px 0px 0px 0px;
            justify-content: space-evenly;
            height: 380px;
            width: 100%;
            overflow-x: auto;
        }
        &__button{
            display: flex;
            margin: 10px 0px 0px 40px;
        }
    }
    .scroll-mob{
        display: flex;
        margin: 0px 0px 0px 170px;
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
    .seasonal{
        display: flex;
        flex-direction: column;
        background: #FFFFFF;
        height: 668px;
        &__title{
            display: flex;
            margin: 21px 0px 0px 1px;
        }
        &__cards{
            display: flex;
            margin: -40px 0px 0px -14px;
            justify-content: space-evenly;
            height: 380px;
            width: 100%;
            overflow-x: auto;
        }
        &__button{
            display: flex;
            margin: 26px 0px 0px 8px;
        }
    }
    .scroll-mob{
        display: flex;
        margin: -32px 0px 0px 167px;
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