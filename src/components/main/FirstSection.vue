<!-- JAVASCRIPT  -->
<script>
// DICHIARO COSA VOGLIO ESPORTARE 
export default {
    // STRUTTURA VUE 
    data() {
        return {
            title: 'Section 1',
            content: 'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Delectus, nisi ullam! Recusandae obcaecati autem quia illum. Excepturi nostrum ratione ullam.'
        }
    }
}
</script>

<!-- HTML  -->
<template>
    <div class="container">
        <div class="textContent">
            <h2>{{ title }}</h2>
            <p>{{ content }}</p>
        </div>

        <img src="src/img/section1Main.png" alt="">
    </div>
</template>

<!-- CSS  -->
<style scoped>
.container {
    max-width: 800px;
    background-color: #F6836B;
    padding: 20px;
    border-radius: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.textContent {
    max-width: 300px;
    color: rgb(255, 239, 239);
}

.textContent h2 {
    font-size: 37px;
    padding-bottom: 25px;
}

.textContent p {
    font-size: 18px;
}
</style>

