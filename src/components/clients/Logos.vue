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
    controls
    autoplay="true"
    style="text-shadow: 1px 1px 2px #333;"
    @sliding-start="onSlideStart"
    @sliding-end="onSlideEnd"
    >
                        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
            
                    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
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
/* .carousel-control-prev-icon {
    background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%2300a8ff' viewBox='0 0 8 8'%3E%3Cpath d='M5.25 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3E%3C/svg%3E") !important;
    color: var(--main-color);
}

.carousel-control-next-icon {
    background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%2300a8ff' viewBox='0 0 8 8'%3E%3Cpath d='M2.75 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3E%3C/svg%3E") !important;
} */
</style>
