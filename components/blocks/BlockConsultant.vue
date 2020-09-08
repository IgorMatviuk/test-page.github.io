<template>
<div class="consultant">
    <div class="mob-none">
        <div class="consultant__image1">
            <img src="./Consultation/cons 1.png" />
        </div>
        <div class="consultant__image2">
            <img src="./Consultation/Ellipse 1.svg" />
          </div>
        <div class="consultant__image3">
            <img src="./Consultation/Ellipse 15.svg" />
        </div>
        <div class="consultant__image4">
            <img src="./Consultation/Ellipse 16.svg" />
        </div>
    </div>
    <div class="desktop-none consultant-mob">
        <img src="./Consultation/Group 270.png" />
    </div>
</div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .consultant{
        display: flex;
        position: relative;
        margin: 0px 0px 0px 0px;
        &__image1{
            display: flex;
            position: absolute;
            margin: 0px 0px 0px 110px;
            z-index: 2;
        }
        &__image2{
            display: flex;
            position: absolute;
            margin: 165px 0px 0px 92px;
            z-index: 1;
        }
        &__image3{
            display: flex;
            position: absolute;
            margin: 140px 0px 0px 64px;
            z-index: 1;
        }
        &__image4{
            display: flex;
            position: absolute;
            margin: 110px 0px 0px 35px;
            z-index: 1;
        }
    }
    .desktop-none{
        display: none;
    }
@media (max-width: 768px) {
    .consultant{
        display: flex;
        position: relative;
        margin: 0px 0px 0px 0px;
        &__image1{
            display: flex;
            position: absolute;
            margin: 0px 0px 0px 110px;
            z-index: 2;
        }
        &__image2{
            display: flex;
            position: absolute;
            margin: 165px 0px 0px 92px;
            z-index: 1;
        }
        &__image3{
            display: flex;
            position: absolute;
            margin: 140px 0px 0px 64px;
            z-index: 1;
        }
        &__image4{
            display: flex;
            position: absolute;
            margin: 110px 0px 0px 35px;
            z-index: 1;
        }
    }
    .desktop-none{
        display: flex;
    }
    .mob-none{
        display: none;
    }
    .consultant-mob{
        display: flex;
        img{
            width: 350px;
            height: 400px;
        }
    }
}
@media (max-width: 375px) {
    .consultant{
        display: flex;
        position: relative;
        margin: 0px 0px 0px 0px;
        &__image1{
            display: flex;
            position: absolute;
            margin: 0px 0px 0px 110px;
            z-index: 2;
        }
        &__image2{
            display: flex;
            position: absolute;
            margin: 165px 0px 0px 92px;
            z-index: 1;
        }
        &__image3{
            display: flex;
            position: absolute;
            margin: 140px 0px 0px 64px;
            z-index: 1;
        }
        &__image4{
            display: flex;
            position: absolute;
            margin: 110px 0px 0px 35px;
            z-index: 1;
        }
    }
    .desktop-none{
        display: flex;
    }
    .mob-none{
        display: none;
    }
    .consultant-mob{
        display: flex;
        margin: 14px 0px 0px -7px;
        img{
            width: 300px;
            height: 350px;
        }
    }    
}
</style>