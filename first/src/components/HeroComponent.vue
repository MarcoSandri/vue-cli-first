<template>
    <div class="fullpage">
        <img src="https://picsum.photos/1200/500">
    </div>
</template>

<script>
    export default {
        name: 'HeroComponent'
    }
</script>

<style scoped>
    .fullpage{
        width: 100vw;
        height: 500px;
    }
    img{
        object-fit: cover;
        width: 100%;
        height: 100%;
    }
</style>