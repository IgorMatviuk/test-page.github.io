<template>
  <div class="block-top-title-subtitle">
      <div class="block-top-title-subtitle__title">
        <div><p>ТОП-2020</p></div>
        <div><p><a>лидеры предзаказов, обзоров и рекомендаций</a></p></div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
    .block-top-title-subtitle{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 106px 0px 31px 7px;
        white-space: nowrap;
        &__title{
            font-family: Roboto;
            font-style: normal;
            font-weight: 900;
            font-size: 44px;
            line-height: 52px;
            text-align: center;
            color: #535353;
            a{
                color: #8B75C8;
                font-weight: 500;
            }
        }
    }
@media (max-width: 768px) {
    .block-top-title-subtitle{
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
                font-size: 25px;
                color: #8B75C8;
            }
        }
    }
}
@media (max-width: 414px) {
    .block-top-title-subtitle{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 0px 0px 0px 0px;
        white-space: normal;
        width: 300px;
        height: 140px;
        &__title{
            font-family: Roboto;
            font-style: normal;
            font-weight: bold;
            font-size: 24px;
            line-height: 28px;
            display: flex;
            align-items: center;
            text-align: center;
            color: #535353;
            flex-direction: column;
            a{
                display: flex;
                font-size: 25px;
                color: #8B75C8;
            }
        }
    }
}
@media (max-width: 375px) {
    .block-top-title-subtitle{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 0px 0px 0px 0px;
        white-space: normal;
        width: 320px;
        height: 140px;
        &__title{
            font-family: Roboto;
            font-style: normal;
            font-weight: bold;
            font-size: 24px;
            line-height: 28px;
            display: flex;
            align-items: center;
            text-align: center;
            color: #535353;
            flex-direction: column;
            margin: 0px 0px 0px 8px;
            a{
                margin: -1px 0px 0px 1px;
                width: 320px;
                font-weight: 600;
                display: flex;
                font-size: 24px;
                color: #8B75C8;
            }
        }
    }
}
</style>