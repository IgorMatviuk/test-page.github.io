<template>
  <div class="block-brand-title-subtitle">
      <div class="block-brand-title-subtitle__title">
        <div><p>Что стоит знать</p></div>
        <div><p><a>при выборе наушников</a></p></div>
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
        padding: 104px 0px 31px 0px;
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
                margin: 0px 0px 0px 5px;
                font-weight: 500;
                color: #8B75C8;
            }
        }
    }
@media (max-width: 768px) {
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
            font-size: 44px;
            line-height: 52px;
            text-align: center;
            color: #535353;
            a{
                color: #8B75C8;
                font-weight: 300;
                font-size: 44px;
            }
        }
    }    
}
@media (max-width: 414px) {
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
            font-size: 30px;
            line-height: 52px;
            text-align: center;
            color: #535353;
            a{
                color: #8B75C8;
                font-weight: 300;
                font-size: 30px;
            }
        }
    }    
}
@media (max-width: 375px) {
    .block-brand-title-subtitle{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 40px 0px 31px 0px;
        white-space: nowrap;
        &__title{
            font-family: Roboto;
            font-style: normal;
            font-weight: 200;
            font-size: 24px;
            line-height: 28px;
            text-align: center;
            color: #535353;
            a{
                color: #8B75C8;
                font-weight: 500;
                font-size: 24px;
            }
        }
    }    
}
</style>