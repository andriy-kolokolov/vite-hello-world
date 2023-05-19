<template>
    <div class="jumbo-wrapper">
        <img :src="imgPath" alt="jumbo">
    </div>
</template>

<script>
export default {
    name: "AppHero",
    data() {
        return {
            imgPath: './src/img/vue_jumbo.png'
        }
    }
}
</script>

<style scoped>
.jumbo-wrapper img{
    max-width: 100%;
}
</style>