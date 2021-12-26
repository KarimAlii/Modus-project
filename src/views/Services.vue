<template>
    <div>
        <Caption />
        <Cards />
    </div>
</template>
<script>
    import Caption from '@/components/services/Caption.vue'
    import Cards from '@/components/services/Cards.vue'
    export default{
    name:"Services",
    components:{
        Caption,
        Cards
    }
    }
</script>