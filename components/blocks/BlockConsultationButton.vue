<template>
  <div class="button">
      <button><p>Пройти тест и получить скидку!</p></button>
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
            width: 337px;
            height: 74px;
            background: linear-gradient(180deg, rgba(255, 255, 255, 0) 0%, #91CF0D 100%), #97D413;
            border: 1px solid #97D413;
            box-sizing: border-box;
            border-radius: 220px;
            p{
                margin: 0px 0px 0px 60px;
                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 15px;
                line-height: 21px;
                display: flex;
                align-items: center;
                text-align: center;
                color: #FFFFFF;
            }
        }
    }
</style>