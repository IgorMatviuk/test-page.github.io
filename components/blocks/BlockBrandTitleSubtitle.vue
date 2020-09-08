<template>
  <div class="block-brand-title-subtitle">
      <div class="block-brand-title-subtitle__title">
        <div><p>100% совместимость</p></div>
        <div><p><a><strong>с любым интерфейсом</strong></a></p></div>
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
        padding: 106px 0px 31px 7px;
        white-space: nowrap;
        &__title{
            padding: 0px 0px 0px 0px;
            font-family: Roboto;
            font-style: normal;
            font-weight: 300;
            font-size: 44px;
            line-height: 52px;
            text-align: center;
            color: #535353;
            a{
                padding: 0px 0px 0px 9px;
                color: #8B75C8;
            }
        }
    }
@media (max-width: 1188px) {
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
            font-size: 34px;
            line-height: 52px;
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
        padding: 36px 0px 0px 0px;
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