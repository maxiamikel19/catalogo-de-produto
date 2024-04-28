<template>
    
    <div class="barnner">
        <div class="barnner__img-content">
            <img src="../../assets/component1.svg" alt="" class="barnner__img-content__img">
        </div>
        <h3 class="barnner__title">Catalogo de produtos</h3>
        <div class="barnner__text-content">
            <p class="barnner__text-content__text">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ex, soluta corrupti ratione fugit,
                 delectus cumque aspernatur 
                sapiente alias optio, repellendus nulla enim id. Molestias magni ipsa porro ducimus, amet nemo!
            </p>
        </div>
    </div>
</template>

<script>
    export default {
  components: {  },
        name:"MainBarnner"
    }
</script>

<style lang="scss" scoped>
    .barnner{
        border:none;
        &__img-content{
            width: 100%;
            height: 150px;
            border: none;
            padding: 0px;
            background: $lilas-1;
            padding: 0px 6px;
            &__img{
                width: 100%;
                height: 100%;
                @include minsize (720px$small) {
                    width: 100%;
                    height: 100%;
                    border: solid 3px $blue;
                }
            }
        }
        &__title{
            text-align: center;
        }
    }
</style>