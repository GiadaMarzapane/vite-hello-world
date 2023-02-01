<script>
export default {
    data() {
        return {
            myImg: "https://www.frcongressi.it/web/wp-content/uploads/2011/04/napoli.jpg"
        }
    }
}
</script>

<template>
   <img :src="myImg" alt="napoli">
</template>

<style scoped>
img{
    height: 500px;
}
</style>