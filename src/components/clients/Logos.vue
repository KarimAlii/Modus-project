<template>
<div class="logos">
    <b-carousel
    class="Logos"
    id="carousel-1"
    v-model="slide"
    :interval="3000"
    indicators
    fade
    loop
    autoplay="true"
    style="text-shadow: 1px 1px 2px #333;"
    @sliding-start="onSlideStart"
    @sliding-end="onSlideEnd"
    >
    
    <b-carousel-slide>
        <template #img>
        <img
            class="d-block image "
            src="../../assets/img/svg/clients/stephenson_william.svg"
            alt="image slot"
        >
        </template>
    </b-carousel-slide>
    <b-carousel-slide>
        <template #img>
        <img
            class="d-block image "
            src="../../assets/img/svg/clients/john_doe_design.svg"
            alt="image slot"
        >
        </template>
    </b-carousel-slide>
        <b-carousel-slide>
        <template #img>
        <img
            class="d-block image "
            src="../../assets/img/svg/clients/john_stephenson.svg"
            alt="image slot"
        >
        </template>
    </b-carousel-slide>    <b-carousel-slide>
        <template #img>
        <img
            class="d-block image "
            src="../../assets/img/svg/clients/stephenson_web_design.svg"
            alt="image slot"
        >
        </template>
    </b-carousel-slide>
    </b-carousel>

</div>
</template>

<script>
export default {
    name:"Logos",
    data() {
    return {
        slide: 0,
        sliding: null
    }
    },
}
</script>
<style>
.logos{
    height: 40vh;
    width:30vw;
    margin:0 auto;
}
.image{
margin:auto;
    height: 25vh;
    width: 15vw;
}
</style>
