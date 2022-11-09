<template>
    <header class="wrapper">

        <div class="blurraz">
            <h1>{{ title }}</h1>
            <p>{{ subTitle }}</p>
        </div>

    </header>

</template>

<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            title: 'My first Vite App!',
            subTitle: 'na ficata!'
        }
    }
}
</script>

<style lang="css">
header {
    background-image: url(https://picsum.photos/1980/460?grayscale);
    background-position: top;
    background-size: cover;
    background-repeat: no-repeat;
    width: 100%;
    height: 50vh;
    background-color: black;
    padding: 20px, 0;
    color: white;
    margin: auto;
    text-align: center;
}
</style>