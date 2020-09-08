<template>
    <div>
        <div class="icon-menu">
            <div class="icon-menu__block-icon">
                <div class="icon-menu__green"><p>1</p></div>
                <img src="../assets/image/Header/Libra.svg" />
            </div>
            <div class="icon-menu__block-icon">
                <div class="icon-menu__green"><p>1</p></div>
              <img src="../assets/image/Header/Like.svg" />
            </div>
            <div class="icon-menu__block-icon">
                <div class="icon-menu__green"><p>1</p></div>
              <img src="../assets/image/Header/shop.svg" />
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.icon-menu{
    display: flex;
        &__block-icon{
            position: relative;
            margin-left: 32px;
            display: flex;
            height: 38px;
            width: 38px;
            background: #FFFFFF;
            box-shadow: 0px 5.81081px 15.1081px rgba(140, 121, 199, 0.3);
            border-radius: 25.5676px;
            img{
                margin: 0px 0px 0px 5px;
            }
        }
       &__green{
           display: flex;
           position: absolute;
           z-index: 3;
           height: 16px;
           width: 16px;
           background: #34C900;
           border-radius: 21.0556px;
           margin: -3px 0px 0px 27px;
           p{
                font-family: Roboto;
                font-style: normal;
                font-weight: bold;
                font-size: 11.4849px;
                line-height: 13px;
                display: flex;
                align-items: center;
                color: #FFFFFF;
                margin-left: 5px;
           }
       }
    }
</style>

