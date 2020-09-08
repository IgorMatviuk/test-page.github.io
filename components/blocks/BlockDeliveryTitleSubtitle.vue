<template>
  <div class="block-brand-title-subtitle">
      <div class="block-brand-title-subtitle__title">
        <div><p>Где выгодно купить качественные наушники?</p></div>
        <div><p><a>Интернет-магазин AudioFree - магазин хороших покупок</a></p></div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
    .block-brand-title-subtitle{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 107px 0px 31px 5px;
        white-space: nowrap;
        &__title{
            font-family: Roboto;
            font-style: normal;
            font-weight: 300;
            font-size: 36px;
            line-height: 42px;
            text-align: center;
            color: #2B2B2B;
            a{
                color: #8B75C8;
                font-weight: 500;
            }
        }
    }
@media (max-width: 1204px) {
    .block-brand-title-subtitle{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 106px 0px 31px 7px;
        white-space: nowrap;
        &__title{
            font-family: Roboto;
            font-style: normal;
            font-weight: 300;
            font-size: 32px;
            line-height: 42px;
            text-align: center;
            color: #2B2B2B;
            a{
                color: #8B75C8;
            }
        }
    }    
}
@media (max-width: 414px) {
    .block-brand-title-subtitle{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 30px 0px 31px 7px;
        white-space: normal;
        &__title{
            width: 360px;
            font-family: Roboto;
            font-style: normal;
            font-weight: 300;
            font-size: 26px;
            line-height: 42px;
            text-align: center;
            color: #2B2B2B;
            a{
                color: #8B75C8;
                font-size: 26px;    
            }
        }
    }    
}
@media (max-width: 375px) {
    .block-brand-title-subtitle{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 30px 0px 31px 8px;
        white-space: normal;
        &__title{
            font-family: Roboto;
            font-style: normal;
            font-weight: 300;
            font-size: 24px;
            line-height: 28px;
            text-align: center;
            color: #2B2B2B;
            a{
                margin: 0px 0px 0px 12px;
                color: #8B75C8;
                font-size: 24px;  
            }
        }
    }    
}
</style>