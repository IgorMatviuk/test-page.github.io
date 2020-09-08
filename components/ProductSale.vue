<template>
  <div class="sale">
          <BlockSaleTitleSubtitle/>
    <div class="container-product sale__container">
        <div><BlockSaleMenu/></div>
        <div>
            <BlockProductSale class="sale__container__cards" :content="data.headphonesSale"/>
        </div>
    </div>
    <div class="scroll-mob">
          <img src="@/components/blocks/scroll/Vector.svg" />
    </div>
  </div>
</template>

<script>

import BlockSaleTitleSubtitle from "@/components/blocks/BlockSaleTitleSubtitle"
import BlockSaleMenu from "@/components/blocks/BlockSaleMenu"
import BlockProductSale from "@/components/blocks/BlockProductSale"

export default {
    components:{
        BlockSaleTitleSubtitle,
        BlockSaleMenu,
        BlockProductSale
    },
        data() {
        return{
            data: {
                headphonesSale: {
                    items: [
                        {
                            sale: '-15%',
                            image: '',
                            title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                            description: 'Многие думают, что Lorem Ipsum - взятый с потолка псевдо-латинский набор слов, но это не совсем так.',
                            price: '1 950 ₽',
                            titleMob: 'Наушники Bluetooth Baseus'
                        },
                        {
                            sale: '-15%',
                            image: '',
                            title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                            description: 'Многие думают, что Lorem Ipsum - взятый с потолка псевдо-латинский набор слов, но это не совсем так.',
                            price: '1 950 ₽',
                            titleMob: 'Наушники Bluetooth Baseus'
                        },
                        {
                            sale: '-15%',
                            image: '',
                            title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                            description: 'Многие думают, что Lorem Ipsum - взятый с потолка псевдо-латинский набор слов, но это не совсем так.',
                            price: '1 950 ₽',
                            titleMob: 'Наушники Bluetooth Baseus'
                        }
                    ]
                }
            }
        }
    }
}
</script>

<style lang="scss" scoped>
    .sale{
        display: flex;
        flex-direction: column;
        background-color: #FFFFFF;
        height: 817px;
        &__container{
            display: flex;
            justify-content: space-between;
            &__cards{
                display: flex;
                flex-direction: row;
                margin: 26px -10px 0px 0px;
            }
        }
    }
    .scroll-mob{
        display: none;
    }
@media (max-width: 1230px) {
    .sale{
        display: flex;
        flex-direction: column;
        background-color: #FFFFFF;
        height: 817px;
        &__container{
            display: flex;
            flex-direction: row;
            overflow-x: auto;
            &__cards{
                display: flex;
                flex-direction: row;
                margin: 26px -10px 0px 0px;
            }
        }
    }
    .scroll-mob{
        display: none;
    }
}
@media (max-width: 414px) {
    .sale{
        display: flex;
        flex-direction: column;
        background-color: #FFFFFF;
        height: 426px;
        &__container{
            display: flex;
            flex-direction: row;
            overflow-x: auto;
            &__cards{
                display: flex;
                flex-direction: row;
                margin: 0px 0px 0px 0px;
            }
        }
    }
    .scroll-mob{
        display: flex;
        margin: 12px 0px 0px 170px;
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
    .sale{
        display: flex;
        flex-direction: column;
        background-color: #FFFFFF;
        height: 426px;
        &__container{
            display: flex;
            flex-direction: row;
            overflow-x: auto;
            &__cards{
                display: flex;
                flex-direction: row;
                margin: 0px 0px 0px -8px;
            }
        }
    }
}
</style>