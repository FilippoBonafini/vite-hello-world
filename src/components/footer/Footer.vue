<script>

// DICHIARO QUALI SARANNO I SOTTOCOMPONENTI UTILIZZATI 
export default {
    data() {
        return {
            title: 'Footer',
            text: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae fuga omnis mollitia nisi saepe itaque ratione repellat accusantium aut rem, at numquam consequatur ad, nostrum molestiae delectus sapiente, autem veniam!'
        }
    }
}
</script>

<!-- HTML  -->
<template>
    <div class="container">
        <h1>
            {{ title }}
        </h1>
        <p>{{ text }}</p>
    </div>
</template>

<!-- CSS  -->
<style scoped>
.container {
    background-color: rgb(99, 98, 98);
    text-align: center;
    padding: 50px;
    color: white;
    padding-bottom: 100px;
}

h1 {
    padding-bottom: 20px;
    font-size: 40px;
}

p {
    font-size: 22px;
}
</style>

