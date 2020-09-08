<template>
  <div class="tabs-container">
    <div class="tabs-container__left">
        <ul class="tabs">
        <div class="tabs-container__left__title">Есть ли гарантия?</div>
          <li><a class="tabs-container__left__none" href="#one">Сколько устройств можно подключить?</a></li>
          <li><a class="tabs-container__left__none" href="#two">Какой провод использовать?</a></li>
          <li><a class="tabs-container__left__none" href="#three">Сколько устройств можно подключить?</a></li>   
        </ul>
    </div>
    <div class="tabs-container__right">
        <div class="tabs-content">
            <ul>
              <li id="one">
                  <div>
                    <p class="tabs-container__right__title">Гарантия на всю продукцию 3 месяца</p>
                    <p class="tabs-container__right__text">Есть много вариантов Lorem Ipsum, но большинство из них имеет не всегда приемлемые модификации, например, юмористические вставки или слова, которые даже отдалённо не напоминают латынь.</p>
                    <p class="tabs-container__right__subtext"> Если вам нужен Lorem Ipsum для серьёзного проекта, вы наверняка не хотите какой-нибудь шутки, скрытой в середине абзаца.</p>
                    <p class="tabs-container__right__link">Перейти в блог</p>
                </div>
              </li>
              <li id="two">
                <p class="tabs-container__right__two-three">Содержимое 2-й вкладки</p>
              </li>
              <li id="three">
                <p>Содержимое 3-й вкладки</p>
              </li>
            </ul>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

.tabs-container{
    display: flex;
    width: 1172px;
    height: 414px;
    background: #FFFFFF;
    box-shadow: 0px 4px 18px rgba(0, 0, 0, 0.05);
    border-radius: 9px;
    &__left{
        display: flex;
        &__title{
            font-family: Roboto;
            font-style: normal;
            font-weight: 500;
            font-size: 20px;
            line-height: 23px;
            display: flex;
            align-items: center;
            color: #4E4E4E;
            margin: 43px 0px 15px 8px;
        }
        
        .tabs {
          margin-bottom: 20px;
          display: flex;
          flex-direction: column;
        }
        .tabs li {
            font-family: Roboto;
            font-style: normal;
            font-weight: normal;
            font-size: 16px;
            line-height: 19px;
            display: flex;
            align-items: center;
            color: #8A8A8A;
            margin: 65px 0px 0px 0px;
        }
        .tabs li a {
          text-decoration: none;
          display: inline-block;
          padding: 0 10px;
          height: 30px;
          line-height: 30px;
        }        
        &__none{
            color: #8A8A8A;
        }
    }
    &__right{
        display: flex;
        &__title{
            font-family: Roboto;
            font-style: normal;
            font-weight: 900;
            font-size: 22px;
            line-height: 30px;
            color: #494949;
            margin: 24px 0px 0px 0px;
        }
        &__text{
            font-family: Roboto;
            font-style: normal;
            font-weight: bold;
            font-size: 15px;
            line-height: 30px;
            color: #494949;
            margin: 31px 0px 0px 0px;
        }
        &__subtext{
            font-family: Roboto;
            font-style: normal;
            font-weight: bold;
            font-size: 15px;
            line-height: 30px;
            color: #494949;
            margin: 30px 0px 0px 0px;
        }
        &__link{
            font-family: Roboto;
            font-style: normal;
            font-weight: bold;
            font-size: 16px;
            line-height: 19px;
            display: flex;
            align-items: center;
            text-decoration-line: underline;
            color: #8B75C8;
            margin: 43px 0px 0px 0px;
        }
        &__two-three{
            margin: 400px 0px 400px 0px;
        }
        .tabs-content {
            width: 671px;
            height: 414px;
          margin: 0px 0px 0px 100px;
          overflow:hidden;
        }
        .tabs-content ul {
            margin: 0px 0px 0px 60px;
          list-style: none;
          height: 380px;
          overflow: scroll;
          overflow-y: hidden;
          overflow-x:hidden;
        }
        .tabs-content ul li div {
          padding: 20px;
        }
    }
}
</style>