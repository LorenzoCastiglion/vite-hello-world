<template>
    <header>
        <h1>{{ title }}</h1>
    </header>

</template>

<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            title: 'My first Vite App!'
        }
    }
}
</script>

<style lang="css">
header {
    width: 100%;
    height: 70px;
    background-color: black;
    padding: 20px;
    color: white;
    margin: auto;
    text-align: center;
}
</style>