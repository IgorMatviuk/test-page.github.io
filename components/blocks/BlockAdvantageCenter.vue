<template>
  <div class="images-of">
    <div class="images-of__advantage1">
      <img src="./Advantage/1.svg" />
    </div>
    <div class="images-of__advantage1-mob">
      <img src="./Advantage/1-mob.svg" />
    </div>
   <div class="images-of__advantage2">
      <img src="./Advantage/2.svg" />
    </div>
   <div class="images-of__advantage2-mob">
      <img src="./Advantage/2-mob.svg" />
    </div>
    <div class="images-of__advantage3">
      <img src="./Advantage/3.svg" />
    </div>
    <div class="images-of__advantage3-mob">
      <img src="./Advantage/3-mob.svg" />
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  .images-of{
    display: flex;
    position: relative;
    margin: -3px 630px 0px 0px;
    &__advantage1{
      display: flex;
      position: absolute;
      z-index: 2;
      margin: 0px 0px 0px 0px;
    }
    &__advantage1-mob{
      display: none;
    }
    &__advantage2{
      display: flex;
      position: absolute;
      z-index: 3;
      margin: 29px 0px 0px 21px;
    }
    &__advantage2-mob{
      display: none;
    }
    &__advantage3{
      display: flex;
      position: absolute;
      z-index: 4;
      margin: 53px 0px 0px 45px;
    }
    &__advantage3-mob{
      display: none;
    }
  }
@media (max-width: 414px) {
  .images-of{
    display: flex;
    position: relative;
    margin: -3px 630px 0px 0px;
    &__advantage1{
      display: none;
    }
    &__advantage1-mob{
      display: flex;
      position: absolute;
      z-index: 2;
      margin: 0px 0px 0px 5px;
    }
    &__advantage2{
      display: none;
    }
    &__advantage2-mob{
      display: flex;
      position: absolute;
      z-index: 3;
      margin: 17px 0px 0px 21px;
    }
    &__advantage3{
      display: none;
    }
    &__advantage3-mob{
      display: flex;
      position: absolute;
      z-index: 4;
      margin: 30px 0px 0px 35px;
    }
  } 
}
@media (max-width: 375px) {
  .images-of{
    display: flex;
    position: relative;
    margin: -3px 630px 0px 0px;
    &__advantage1{
      display: none;
    }
    &__advantage1-mob{
      display: flex;
      position: absolute;
      z-index: 2;
      margin: 0px 0px 0px 5px;
    }
    &__advantage2{
      display: none;
    }
    &__advantage2-mob{
      display: flex;
      position: absolute;
      z-index: 3;
      margin: 16px 0px 0px 21px;
    }
    &__advantage3{
      display: none;
    }
    &__advantage3-mob{
      display: flex;
      position: absolute;
      z-index: 4;
      margin: 30px 0px 0px 35px;
    }
  } 
}
</style>