<template>
    <div class="hero">
        <h2>The Power of Vue CLI</h2>
    </div>
</template>

<script>

export default {
    name: "HeroEl"
}
</script>

<style scoped>

.hero {
    width: 70%;
    height: 60vh;
    margin: 0 auto;
    border: 1px solid black;
    border-radius: 10px;
    background-color: lightgray;
    background-image: url(../assets/logo.png);
    background-position: center;
    background-repeat: no-repeat;
}

.hero h2{
    font-size: 40px;
}
</style>