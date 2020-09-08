<template>
  <div class="product-brand">
      <BlockBrandTitleSubtitle />
      <div class="container-product product-brand__container">
          <div>
              <BlockBrandMenu/>
          </div>
          <div>
            <BlockProductOneClick class="product-brand__container__cards" :content="data.headphonesOneClick"/>
        </div>
      </div>
      <div class="scroll-mob">
          <img src="@/components/blocks/scroll/Vector.svg" />
      </div>
  </div>
</template>

<script>

import BlockBrandTitleSubtitle from "@/components/blocks/BlockBrandTitleSubtitle"
import BlockBrandMenu from "@/components/blocks/BlockBrandMenu"
import BlockProductOneClick from "@/components/blocks/BlockProductOneClick"

export default {
    components: {
        BlockBrandTitleSubtitle,
        BlockBrandMenu,
        BlockProductOneClick
    },
    data() {
        return{
            data: {
                headphonesOneClick: {
                    items: [
                        {
                            state: 'В наличии',
                            image: '',
                            title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                            price: '1 950 ₽',
                            titleMob: 'Наушники Bluetooth Baseus'
                        },
                        {
                            state: 'В наличии',
                            image: '',
                            title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
                            price: '1 950 ₽',
                            titleMob: 'Наушники Bluetooth Baseus'
                        },
                        {
                            state: 'В наличии',
                            image: '',
                            title: 'Наушники Bluetooth Baseus Encok D01 NGD01-09 (red)',
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

<style lang="scss">
    .product-brand{
        display: flex;
        flex-direction: column;
        height: 820px;
        &__container{
            display: flex;
            justify-content: space-between;
            margin-top: 16px;
            &__cards{
                display: flex;
                flex-direction: row;
                margin: 1px 0px 0px -16px;
            }
        }
    }
    .scroll-mob{
        display: none;
    }
@media (max-width: 1188px) {  
        .product-brand{
        display: flex;
        flex-direction: column;
        height: 820px;
        &__container{
            display: flex;
            justify-content: space-between;
            margin-top: 16px;
            overflow-x: auto;
            &__cards{
                display: flex;
                flex-direction: row;
                margin: 1px 0px 0px -16px;
            }
        }
    } 
    .scroll-mob{
        display: none;
    }
}
@media (max-width: 375px) {
        .product-brand{
        display: flex;
        flex-direction: column;
        height: 636px;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 3px 0px 0px 0px;
            overflow: hidden;
            &__cards{
                display: flex;
                flex-direction: row;
                margin: -33px 0px 0px -11px;
                overflow-x: auto;
                overflow-y: hidden;
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
@media (max-width: 360px) {
        .product-brand{
        display: flex;
        flex-direction: column;
        height: 636px;
        &__container{
            display: flex;
            flex-direction: column;
            margin: 0px 0px 0px -7px;
            overflow: hidden;
            &__cards{
                display: flex;
                flex-direction: row;
                margin: -33px 0px 0px -11px;
                overflow-x: auto;
                overflow-y: hidden;
            }
        }
    }  
}
</style>