<!-- JAVASCRIPT  -->
<script>
// IMPORTO I SOTTOCOMPONENTI DI QUESTO COMPONENTE 
import Jumbotron from './Jumbotron.vue';
import AppTitle from './AppTitle.vue';
// DICHIARO QUALI SARANNO I SOTTOCOMPONENTI UTILIZZATI 
export default {
    components: {
        Jumbotron,
        AppTitle
    }
}
</script>

<!-- HTML  -->
<template>
    <div>
        <AppTitle></AppTitle>
    </div>

    <div class="jumbo">
        <Jumbotron></Jumbotron>
    </div>
</template>

<!-- CSS  -->
<style scoped>
.jumbo {
    margin-top: 150px;
}
</style>