<!-- JAVASCRIPT  -->
<script>
// DICHIARO COSA VOGLIO ESPORTARE 
export default {
    // STRUTTURA VUE 
    data() {
        return {
        }
    }
}
</script>

<!-- HTML  -->
<template>
    <div class="container">
        <h1>Clicca qua!</h1>
        <a href="https://github.com/FilippoBonafini/vite-hello-world" target="_blank" class="button">Click Me!</a>
    </div>
</template>

<!-- CSS  -->
<style scoped>
.container {
    text-align: center;
}

h1 {
    font-size: 50px;
}

.button {
    margin-top: 20px;
    background-color: #5EC9CC;
    display: inline-block;
    padding: 30px;
    font-size: 50px;
    text-decoration: none;
    border-radius: 30px;
    cursor: pointer;
    color: black;
}

.button:hover {
    background-color: #F6836B;
    color: white;
}
</style>

