<!-- JAVASCRIPT  -->
<script>
// DICHIARO COSA VOGLIO ESPORTARE 
export default {
    // STRUTTURA CLASSICA DI VUE 
    data() {
        return {
            title: 'La mia prima app con Vite!'
        }
    }
}
</script>

<!-- HTML  -->
<template>
    <div>
        <h1>{{ title }}</h1>
    </div>
</template>

<!-- CSS  -->
<style scoped>
div {
    background-color: #F6836B;
    padding: 30px;
    display: flex;
    justify-content: center;
    align-items: center;
    position: fixed;
    top: 0;
    right: 0;
    left: 0;
    z-index: 2;
}

h1 {
    font-size: 60px;
    color: white;
}
</style>