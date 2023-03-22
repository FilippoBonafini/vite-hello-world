<script>
// IMPORTO I SOTTOPROGRAMMI
import FirstSection from './FirstSection.vue';
import SecondSection from './SecondSection.vue';
// DICHIARO QUALI SARANNO I SOTTOCOMPONENTI UTILIZZATI 
export default {
    components: {
        FirstSection,
        SecondSection
    }
}
</script>

<!-- HTML  -->
<template>
    <div class="section">
        <FirstSection></FirstSection>
    </div>

    <div class="section">
        <SecondSection></SecondSection>
    </div>
    <div class="section">
        <FirstSection></FirstSection>
    </div>
</template>

<!-- CSS  -->
<style scoped>
.section {
    padding-bottom: 100px;
}
</style>

