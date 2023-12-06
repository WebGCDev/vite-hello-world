<script>
export default {
    name: 'AppHero',
    data() {
        return {
            titleJumbo: 'Jumbotron'
        }
    }
}
</script>

<template>
    <div id="jumbotron">
        <h2>{{ titleJumbo }}</h2>
        <img src="../../vite.svg" alt="vite">
    </div>
</template>

<style scoped>
#jumbotron {
    margin-top: 100px;
    text-align: center;
    color: black;
}

h2 {
    font-size: 5rem;
}

img {
    margin-top: 10px;
    width: 200px;
}
</style>