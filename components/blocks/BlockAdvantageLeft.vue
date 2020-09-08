<template>
  <div class="container">
    <div class="container__blocks">
      <div class="container__blocks__block">
        <div class="container__blocks__block__number">
          <p>01</p>
        </div>
         <div class="container__blocks__block__image">
           <div class="container__blocks__block__image__ellipse-big">
             <img src="./Advantage/Ellipse 6.svg" />
             </div>
           <div class="container__blocks__block__image__ellipse-small">
             <img src="./Advantage/Ellipse 7.svg" />
             </div>
         </div>
         <div class="container__blocks__block__text">
           <div class="container__blocks__block__text__title"><p>Отсутствие проводов</p></div>
           <div class="container__blocks__block__text__subtitle"><p>Многие думают, что Lorem Ipsum - взятый с потолка псевдо-латинский набор слов, но это не совсем так.</p></div>
         </div>
      </div>
      <div class="container__blocks__block block2-margin">
        <div class="container__blocks__block__number">
          <p>02</p>
        </div>
         <div class="container__blocks__block__image">
           <div class="container__blocks__block__image__ellipse-big">
             <img src="./Advantage/Ellipse 6.svg" />
             </div>
           <div class="container__blocks__block__image__ellipse-small">
             <img src="./Advantage/Ellipse 7.svg" />
             </div>
         </div>
         <div class="container__blocks__block__text">
           <div class="container__blocks__block__text__title"><p>Удобство</p></div>
           <div class="container__blocks__block__text__subtitle"><p>Многие думают, что Lorem Ipsum - взятый с потолка псевдо-латинский набор слов, но это не совсем так.</p></div>
         </div>
      </div>
      <div class="container__blocks__block block3-margin">
        <div class="container__blocks__block__number">
          <p>03</p>
        </div>
         <div class="container__blocks__block__image">
           <div class="container__blocks__block__image__ellipse-big">
             <img src="./Advantage/Ellipse 6.svg" />
             </div>
           <div class="container__blocks__block__image__ellipse-small">
             <img src="./Advantage/Ellipse 7.svg" />
             </div>
         </div>
         <div class="container__blocks__block__text">
           <div class="container__blocks__block__text__title"><p>Красивый аксессуар</p></div>
           <div class="container__blocks__block__text__subtitle"><p>Многие думают, что Lorem Ipsum - взятый с потолка псевдо-латинский набор слов, но это не совсем так.</p></div>
         </div>
      </div>
    </div>
    <div class="container__line">
      <img src="./Advantage/Line 10.svg" />
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
  .container{
    display: flex;
    &__blocks{
      display: flex;
      flex-direction: column;
      margin: 20px 0px 0px 0px;
      position: relative;
      &__block{
        display: flex;
        flex-direction: row;
        align-items: center;
        &__number{
          display: flex;
          font-family: Roboto;
          font-style: normal;
          font-weight: 900;
          font-size: 18px;
          line-height: 21px;
          color: #816FB2;
          margin: 0px 0px 8px -13px;
        }
        &__image{
          display: flex;
          margin: 0px 0px 10px -18px;
          &__ellipse-big{
            display: flex;
            position: relative;
            z-index: 2;
          }
          &__ellipse-small{
            display: flex;
            position: absolute;
            z-index: 3;
            margin: 43px 0px 0px 48px;
          }
        }
        &__text{
          display: flex;
          flex-direction: column;
          margin: 35px 0px 0px -5px;
          &__title{
            display: flex;
            width: 300px;
            font-family: Roboto;
            font-style: normal;
            font-weight: normal;
            font-size: 24px;
            line-height: 28px;
            color: #FFFFFF;
          }
          &__subtitle{
            margin: 12px 0px 0px 0px;
            display: flex;
            width: 230px;
            font-family: Roboto;
            font-style: normal;
            font-size: 11px;
            line-height: 15px;
            color: #FFFFFF;
          }
        }
      }
    }
    &__line{
      display: flex;
      position: absolute;
      z-index: 1;
      margin: 50px 0px 0px 40px;
    }
  }
  .block2-margin{
    margin: 16px 0px 0px 0px;
  }
  .block3-margin{
    margin: 10px 0px 0px 0px;
  }
</style>