<script>
// DICHIARO COSA VOGLIO ESPORTARE 
export default {
    // STRUTTURA VUE 
    data() {
        return {
            title: 'Section 2',
            content: 'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Delectus, nisi ullam! Recusandae obcaecati autem quia illum. Excepturi nostrum ratione ullam, a, tenetur debitis quas quidem, eum iste culpa maiores atque.'
        }
    }
}
</script>

<!-- HTML  -->
<template>
    <div>
        <h2>{{ title }}</h2>
        <p>{{ content }}</p>
    </div>
</template>

<!-- CSS  -->
<style scoped>
div {
    text-align: center;
    font-size: 20px;
    background-color: #5EC9CC;
    padding: 40px;
}

h2 {
    padding-bottom: 20px;
}
</style>

