<template>
  <div class="tabs">
    <div class="tabs__tab">
      <details open>
        <summary><a>Есть ли гарантия?</a></summary>
          <p>Есть много вариантов Lorem Ipsum, но большинство из них имеет не всегда приемлемые модификации, например, юмористические вставки или слова, которые даже отдалённо не напоминают латынь.</p>
          <p> Если вам нужен Lorem Ipsum для серьёзного проекта, вы наверняка не хотите какой-нибудь шутки, скрытой в середине абзаца.</p>
        </details>
    </div>
    <div class="tabs__tab">
      <details class="tab2-margin">
        <summary><a>Какой провод использовать</a></summary>
          <p>Есть много вариантов Lorem Ipsum, но большинство из них имеет не всегда приемлемые модификации, например, юмористические вставки или слова, которые даже отдалённо не напоминают латынь.</p>
          <p> Если вам нужен Lorem Ipsum для серьёзного проекта, вы наверняка не хотите какой-нибудь шутки, скрытой в середине абзаца.</p>
        </details>
    </div>
    <div class="tabs__tab">
      <details>
        <summary><a>Есть ли гарантия?</a></summary>
          <p>Есть много вариантов Lorem Ipsum, но большинство из них имеет не всегда приемлемые модификации, например, юмористические вставки или слова, которые даже отдалённо не напоминают латынь.</p>
          <p> Если вам нужен Lorem Ipsum для серьёзного проекта, вы наверняка не хотите какой-нибудь шутки, скрытой в середине абзаца.</p>
        </details>
    </div>
    <div class="tabs__tab">
      <details>
        <summary><a>Есть ли гарантия?</a></summary>
          <div class="tabs__tab__text">
          <p>Есть много вариантов Lorem Ipsum, но большинство из них имеет не всегда приемлемые модификации, например, юмористические вставки или слова, которые даже отдалённо не напоминают латынь.</p>
          <p> Если вам нужен Lorem Ipsum для серьёзного проекта, вы наверняка не хотите какой-нибудь шутки, скрытой в середине абзаца.</p>
          </div>
        </details>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
 .tabs{
   display: flex;
   flex-direction: column;
   &__tab{
    details[open] {
       display: flex;
       flex-direction: column;
       width: 358px;
       height: 472px;
       background: #FFFFFF;
       box-shadow: 0px 0px 8px rgba(0, 0, 0, 0.15);
       border-radius: 8px;
       p{
         font-family: Roboto;
         font-style: normal;
         font-weight: normal;
         font-size: 16px;
         line-height: 30px;
         color: #494949;
         margin: 26px 10px 0px 22px;
         width: 290px;
        }
    }
      details{
        display:block;
        margin-bottom: 5px;
        }
      summary::-webkit-details-marker{display:none;}
      summary::-moz-list-bullet{list-style-type:none;}
      summary::marker{display:none;} 
      summary {
         padding: .3em .5em .3em .4em;
         display:inline-block;
         font-size:1.4em;
         cursor: pointer;
        width: 358px;
        height: 61px;
        background: #FFFFFF;
        box-shadow: 0px 0px 8px rgba(0, 0, 0, 0.15);
        border-radius: 8px;
        a{
          font-family: Roboto;
          font-style: normal;
          font-weight: bold;
          font-size: 20px;
          line-height: 23px;
          color: #4E4E4E;
          margin: 0px 0px 0px 20px;
        }
      }
      summary:after {  
        content: "+";
        margin: 0px 0px 0px 111px;
        display: inline-block;
        transition: transform .5s;
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 36px;  
        line-height: 42px;
        color: #8B75C8;
      }
      details[open] > summary:after {
        content: "–";
      }
    }
 }
 .tab2-margin{
   summary:after{
     margin: 0px 0px 0px 13px;
   }
 }
</style>