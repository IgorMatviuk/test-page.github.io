<template>
    <div class="options">
        <div class="white-title options__title-position">
            <p>Выберите свои наушники</p>
            <a>Функциональные, комфортные, стильные</a>
        </div>
        <div class="options__container mob-none">
            <div><img src="../assets/image/HeadphonesOptions/Component 44.png" /></div>
        </div>
        <div class="options__container desktop-none">
            <div><img src="../assets/image/HeadphonesOptions/Component 44 mob.png" /></div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .options{
        display: flex;
        flex-direction: column;
        height: 672px;
        background-color: #8B75C8;
        &__title-position{
            display: flex;
            margin: 83px 0px 0px 20px;
        }
        &__container{
            display: flex;
            margin: 65px 0px 0px 20px;
            overflow-x: auto;
        }
        &__container::-webkit-scrollbar {
            background-color: transparent;
        }
    }
    .desktop-none{
        display: none;
    }
@media (max-width: 375px) {
      .options{
        display: flex;
        flex-direction: column;
        height: 505px;
        background-color: #8B75C8;
        &__title-position{
            display: flex;
            margin: 38px 0px 0px 3px;
        }
        &__container{
            display: flex;
            margin: 30px 0px 0px 10px;
            overflow-x: auto;
            height: 335px;
            overflow-y: hidden;
        }
        &__container::-webkit-scrollbar {
            background-color: transparent;
        }
    }  
    .desktop-none{
        display: flex;
    }
    .mob-none{
        display: none;
    }
}
</style>