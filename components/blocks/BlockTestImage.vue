<template>
  <div class="image">
    <div class="image__text">
        <img src="@/assets/image/Test/5 best models.png" />
      </div>
    <div class="image__model">
        <img src="@/assets/image/Test/3197276.png" />
      </div>
    <div class="image__Rectangle">
        <img src="@/assets/image/Test/Rectangle 167.png" />
      </div>
    <div class="image__text-mob">
        <img src="@/assets/image/Test/5 best models.svg" />
      </div>
    <div class="image__model-mob">
        <img src="@/assets/image/Test/3197276-mob.png" />
      </div>
    <div class="image__Rectangle-mob">
        <img src="@/assets/image/Test/Rectangle 167.svg" />
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .image{
        display: flex;
        position: relative;
        margin: 33px 600px 0px 0px;
        &__text{
            display: flex;
            position: absolute;
            margin: 50px 0px 0px 90px;
            z-index: 1;
        }
        &__text-mob{
          display: none;
        }
        &__model{
            display: flex;
            position: absolute;
            margin: -75px 0px 0px -135px;
            z-index: 3;
        }
        &__model-mob{
          display: none;
        }
        &__Rectangle{
            display: flex;
            position: absolute;
            margin: 0px 0px 0px 0px;
            z-index: 2;
        }
        &__Rectangle-mob{
          display: none;
        }
    }
@media (max-width: 414px) {
    .image{
        display: flex;
        position: relative;
        margin: 10px 600px 0px 0px;
        &__text{
            display: none;
        }
        &__text-mob{
            display: flex;
            position: absolute;
            margin: 50px 0px 0px 90px;
            z-index: 1;
        }
        &__model{
            display: none;
        }
        &__model-mob{
            display: flex;
            position: absolute;
            margin: -95px 0px 0px 0px;
            z-index: 3;
        }
        &__Rectangle{
            display: none;
        }
        &__Rectangle-mob{
            display: flex;  
            position: absolute;
            margin: 0px 0px 0px 0px;
            z-index: 2;
        }
    }  
}
@media (max-width: 375px) {
    .image{
        display: flex;
        position: relative;
        margin: 10px 600px 0px 0px;
        &__text{
            display: none;
        }
        &__text-mob{
            display: flex;
            position: absolute;
            margin: 50px 0px 0px 90px;
            z-index: 1;
        }
        &__model{
            display: none;
        }
        &__model-mob{
            display: flex;
            position: absolute;
            margin: -96px 0px 0px -9px;
            z-index: 3;
        }
        &__Rectangle{
            display: none;
        }
        &__Rectangle-mob{
            display: flex;  
            position: absolute;
            margin: 0px 0px 0px 0px;
            z-index: 2;
        }
    }    
}
</style>