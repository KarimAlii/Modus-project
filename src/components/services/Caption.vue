<template>
<div class="history">
    <b-container class="text-center ">
        <h3 class="mb-5">Little history</h3>
        <p class="">
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum        </p>
    </b-container>
</div>
</template>
<script>
export default{
    name:"Caption"
}
</script>
<style>
  /* Small */

.history{
padding-top: 5vh;
height: 35vh;
width: 100vw;
background-color: var(--offwhite);
}
.history h3{
    font-size: calc(var(--default-font) + 5px);
    text-transform: uppercase;
    }

          /* Small */
    @media (min-width: 320px) {
    .history p {
    font-size:calc(var(--default-font) - 6.5px) ;
    }
    }
      /* Medium */
    @media (min-width: 768px) {
    .history p {
    font-size:calc(var(--default-font) - 3px) ;
    }
}
  /* Large */
    @media (min-width: 992px) {
    .history p {
    font-size:var(--default-font)  ;
        }
}
  /*X Large */

    @media (min-width: 1024px) {
    .history p {
    font-size:calc(var(--default-font) + 2px) ;
        }
}
.history p{
    color: var(--grey2);
    width:50%;
    margin-left: 25%;
    }
</style>