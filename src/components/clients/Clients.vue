<template>
<b-container class="text-center">
    <div class="info">
                    <h3 class="mb-5">our clients are</h3>
                <p>" It is a long established fact that It is a long established fact that a reader will be distracted
                    by the readable content of a page It is a long established fact that It is a long established fact
                    that a reader will be distracted
                    by the readable content of a page
                    when"</p>
    </div>
</b-container>
</template>
<script>
export default{
    name:"Clients"
}
</script>
<style scoped>
.info{
    height: 40vh;
    padding-top: 10vh;
}          /* Small */
    @media (min-width: 320px) {
    .info {
    font-size:calc(var(--default-font) - 2px) ;
    }
    }
      /* Medium */
    @media (min-width: 768px) {
    .info {
    font-size:calc(var(--default-font) - 2px) ;
    }
}
  /* Large */
    @media (min-width: 992px) {
    .info {
    font-size:calc(var(--default-font) + 4px) ;
        }
}
  /*X Large */

    @media (min-width: 1024px) {
    .info {
    font-size:calc(var(--default-font) + 6px) ;
        }
}

h3{
    text-transform: uppercase;
}
p{
font-family:  'Dancing Script', cursive; 
    width:50%;
    margin-left: 25%;

}
</style>
