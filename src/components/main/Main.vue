<script>
// IMPORTO I SOTTOPROGRAMMI
import FirstSection from './FirstSection.vue';
import SecondSection from './SecondSection.vue';
import CallToAction from './CallToAction.vue';
// DICHIARO QUALI SARANNO I SOTTOCOMPONENTI UTILIZZATI 
export default {
    components: {
        FirstSection,
        SecondSection,
        CallToAction
    }
}
</script>

<!-- HTML  -->
<template>
    <div class="section callToActionContainer">
        <FirstSection></FirstSection>
        <CallToAction></CallToAction>
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
    display: flex;
    justify-content: center;
}

.section.callToActionContainer {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 100px;
}
</style>

