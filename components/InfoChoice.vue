<template>
  <div class="choice">
      <div class="choice__container">
        <div class="choice__container__title">
            <BlockChoiceTitleSubtitle/>
        </div>
        <div class="choice__container__tabs">
            <BlockTabsInfoChoice/>
        </div>
        <div class="tabs-mob">
            <BlockTabsInfoChoiceMob/>
        </div>
        <div class="link"><p>Перейти в блог</p></div>
    </div>
  </div>
</template>

<script>


import BlockChoiceTitleSubtitle from "@/components/blocks/BlockChoiceTitleSubtitle"
import BlockTabsInfoChoice from "@/components/blocks/BlockTabsInfoChoice"
import BlockTabsInfoChoiceMob from "@/components/blocks/BlockTabsInfoChoiceMob"

export default {
    components:{
        BlockChoiceTitleSubtitle,
        BlockTabsInfoChoice,
        BlockTabsInfoChoiceMob
    }
}
</script>

<style lang="scss" scoped>
    .choice{
        display: flex;
        height: 776px;
        background: #F8F5FE;
        &__container{
            display: flex;
            flex-direction: column;
            &__title{
                display: flex;
                margin: 0px 0px 0px 732px;
            }
            &__tabs{
                display: flex;
                margin: 8px 0px 0px 368px;
            }
        }
    }
.tabs-mob{
    display: none;
}
.link{
    display: none;
}
@media (max-width: 1565px) {
    .choice{
        display: flex;
        height: 776px;
        background: #F8F5FE;
        &__container{
            display: flex;
            flex-direction: column;
            &__title{
                display: flex;
                margin: 0px 0px 0px 530px;
            }
            &__tabs{
                display: flex;
                margin: 8px 0px 0px 168px;
            }
        }
    }  
    .tabs-mob{
        display: none;
    } 
    .link{
    display: none;
    }
}
@media (max-width: 1360px) {
    .choice{
        display: flex;
        height: 776px;
        background: #F8F5FE;
        &__container{
            display: flex;
            flex-direction: column;
            &__title{
                display: flex;
                margin: 0px 0px 0px 330px;
            }
            &__tabs{
                display: flex;
                margin: 8px 0px 0px 28px;
            }
        }
    }  
    .tabs-mob{
        display: none;
    }  
    .link{
    display: none;
    }
}
@media (max-width: 1220px) {
    .choice{
        display: flex;
        height: 1020px;
        background: #F8F5FE;
        &__container{
            display: flex;
            flex-direction: column;
            &__title{
                display: flex;
                margin: 0px 0px 0px 330px;
            }
            &__tabs{
                display: none;
            }
        }
    }  
    .tabs-mob{
        display: flex;
        margin: 0px 0px 0px 400px;
    }   
    .link{
        display: flex;
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 16px;
        line-height: 19px;
        display: flex;
        align-items: center;
        text-decoration-line: underline;
        color: #8B75C8;
        margin: 20px 0px 0px 500px;
    }  
}
@media (max-width: 768px) {
    .choice{
        display: flex;
        height: 1020px;
        background: #F8F5FE;
        &__container{
            display: flex;
            flex-direction: column;
            &__title{
                display: flex;
                margin: 0px 0px 0px 150px;
            }
            &__tabs{
                display: none;
            }
        }
    }  
    .tabs-mob{
        display: flex;
        margin: 0px 0px 0px 200px;
    }   
    .link{
        display: flex;
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 16px;
        line-height: 19px;
        display: flex;
        align-items: center;
        text-decoration-line: underline;
        color: #8B75C8;
        margin: 20px 0px 0px 280px;
    }  
}
@media (max-width: 414px) {
    .choice{
        display: flex;
        height: 1020px;
        background: #F8F5FE;
        &__container{
            display: flex;
            flex-direction: column;
            &__title{
                display: flex;
                margin: 0px 0px 0px 30px;
            }
            &__tabs{
                display: none;
            }
        }
    }  
    .tabs-mob{
        display: flex;
        margin: 0px 0px 0px 30px;
    }   
    .link{
        display: flex;
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 16px;
        line-height: 19px;
        display: flex;
        align-items: center;
        text-decoration-line: underline;
        color: #8B75C8;
        margin: 20px 0px 0px 150px;
    }  
}
@media (max-width: 375px) {
    .choice{
        display: flex;
        height: 887px;
        background: #F8F5FE;
        &__container{
            display: flex;
            flex-direction: column;
            &__title{
                display: flex;
                margin: 0px 0px 0px 8px;
            }
            &__tabs{
                display: none;
            }
        }
    }  
    .tabs-mob{
        display: flex;
        margin: -6px 0px 0px 10px;
    }   
    .link{
        display: flex;
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 16px;
        line-height: 19px;
        display: flex;
        align-items: center;
        text-decoration-line: underline;
        color: #8B75C8;
        margin: 30px 0px 0px 130px;
    }  
}
</style>