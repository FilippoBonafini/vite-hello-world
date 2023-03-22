<!-- JAVASCRIPT  -->
<script>
// DICHIARO COSA VOGLIO ESPORTARE 
export default {
    // STRUTTURA CLASSICA DI VUE 
    data() {
        return {
            titleJumbotron: 'Questo argomento cambia tutto!',
        }
    }
}
</script>

<!-- HTML  -->
<template>
    <div>
        <h2>{{ titleJumbotron }}</h2>
        <img src="src/img/workHard.png" alt="">
    </div>
</template>

<!-- CSS  -->
<style scoped>
div {
    background-color: rgb(99, 98, 98);
    padding-bottom: 50px;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 100px;
}

h2 {
    font-size: 60px;
    max-width: 500px;
    color: white;
}

img {
    height: 100%;
    position: relative;
    top: 100px;
}
</style>
