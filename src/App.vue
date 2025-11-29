<script setup>
import FeatureSection from './components/FeatureSection.vue';
import HeroSection from './components/HeroSection.vue';
import NavigationBar from './components/NavigationBar.vue';
import Footer from './components/Footer.vue';
</script>

<template>
  <NavigationBar />
  <main id="main">
    <HeroSection />
    <FeatureSection />
  </main>
  <Footer />
</template>

<style scoped>
#main {
  padding-block: 80px;
  display: flex;
  flex-direction: column;
  gap: 96px;
}
</style>
