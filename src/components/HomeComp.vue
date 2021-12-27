<template>
<section class="text-center slider position-relative">
    <div class="caption position-absolute translate-middle top-50 start-50">
        <h3>Design / Development / Photography</h3>
        <h1>Creativity Has new level</h1>
        <a class="btn career">Preveiw</a>
        <a class="btn career">get theme</a>
    
    </div>
</section>
</template>
<style scoped>
.slider{
background-image: url("../assets/img/header.jpg");
background-size: cover;
height: 80vh;
background-color: var(--second-color);
background-blend-mode: multiply;
color: var(--white);
}
.slider .caption .career{
    color: var(--white);
    background-color: transparent;
    border: 1px solid var(--white);
    border-radius: 10px;
    font-weight: bold;
    font-size: calc(var(--default-font-size) + 2px);
    margin-right: 5%;
    padding: 2% 8%;
    text-transform: uppercase;
}
.slider .caption .career:hover{
    background-color: var(--main-color);
    transition: ease-in-out 1s;
    transform: rotate(20deg);
}
/* small */
    @media (min-width: 320px) {
    .caption{
    font-size:calc(var(--default-font) - 6px) ;
    }
    }
      /* Medium */
    @media (min-width: 768px) {
    .caption{
    font-size:calc(var(--default-font) - 3px) ;
    }
}
  /* Large */
    @media (min-width: 992px) {
    .caption {
    font-size:var(--default-font)  ;
        }
}
  /*X Large */

    @media (min-width: 1024px) {
    .caption {
    font-size:calc(var(--default-font) + 2px) ;
        }
    }

</style>
<script>
export default {
    name:"HomeComp"
    }
</script>