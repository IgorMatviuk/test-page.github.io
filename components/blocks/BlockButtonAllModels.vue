<template>
  <div class="button">
      <button><p>Смотреть больше моделей</p></button>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .button{
        display: flex;
        button{
            display: flex;
            align-items: center;
            width: 343px;
            height: 72px;
            background: linear-gradient(180deg, rgba(255, 255, 255, 0) 0%, rgba(0, 0, 0, 0.13) 98.96%), #8B75C8;
            border-radius: 220px;
            border: none;
            p{
                margin: 0px 0px 0px 50px;
                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 18px;
                line-height: 21px;
                display: flex;
                align-items: center;
                text-align: center;
                color: #FFFFFF;
            }
        }
    }
@media (max-width: 375px) {
    .button{
        display: flex;
        button{
            display: flex;
            align-items: center;
            width: 361px;
            height: 72px;
            background: linear-gradient(180deg, rgba(255, 255, 255, 0) 0%, rgba(0, 0, 0, 0.13) 98.96%), #8B75C8;
            border-radius: 220px;
            border: none;
            p{
                margin: 0px 0px 0px 59px;
                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 18px;
                line-height: 21px;
                display: flex;
                align-items: center;
                text-align: center;
                color: #FFFFFF;
            }
        }
    }    
}
</style>