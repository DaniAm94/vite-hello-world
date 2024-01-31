<script>
export default {
    name: 'AppHero',
    data: () => ({
        img_name: 'R.jpeg'
    }),
    methods: {
        createImagePath(img) {
            const url = new URL(`../assets/img/${img}`, import.meta.url);
            return url.href;
        }
    }
}
</script>

<template>
    <figure>
        <img :src="createImagePath(img_name)" alt="jumbotron">
    </figure>
</template>

<style>
img {
    max-width: 100%;
    height: auto;
}
</style>