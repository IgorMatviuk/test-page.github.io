<template>
  <div class="block-brand-title-subtitle">
      <div class="block-brand-title-subtitle__title">
        <div><p>Постоянные акции</p></div>
        <div><p><a><strong>и сезонные предложения</strong></a></p></div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .block-brand-title-subtitle{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 108px 0px 31px 7px;
        white-space: nowrap;
        &__title{
            font-family: Roboto;
            font-style: normal;
            font-weight: 300;
            font-size: 44px;
            line-height: 52px;
            text-align: center;
            color: #535353;
            a{
                padding: 0px 0px 0px 10px;
                color: #8B75C8;
            }
        }
    }
@media (max-width: 414px) {
    .block-brand-title-subtitle{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 20px 0px 31px 7px;
        white-space: nowrap;
        &__title{
            font-family: Roboto;
            font-style: normal;
            font-weight: 300;
            font-size: 24px;
            line-height: 28px;
            text-align: center;
            color: #535353;
            a{
                color: #8B75C8;
            }
        }
    }    
}
@media (max-width: 375px) {
    .block-brand-title-subtitle{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 35px 0px 25px 2px;
        white-space: nowrap;
        &__title{
            font-family: Roboto;
            font-style: normal;
            font-weight: 300;
            font-size: 24px;
            line-height: 28px;
            text-align: center;
            color: #535353;
            a{
                color: #8B75C8;
            }
        }
    }    
}
</style>