<script setup lang="ts">
import LandingHeader from './components/LandingHeader.vue'
import BenefitSection from './components/BenefitSection.vue'
import LandingBanner from './components/LandingBanner.vue'
import LandingFooter from './components/LandingFooter.vue'
import CallToActionManualUser from './components/CallToActionManualUser.vue'
import CallToActionGetProduct from './components/CallToActionGetProduct.vue'
</script>

<template>
  <div class="w-full min-h-screen">
    <LandingHeader />

    <LandingBanner />

    <BenefitSection />

    <CallToActionManualUser />

    <CallToActionGetProduct />

    <LandingFooter />


  </div>
</template>

<style scoped></style>
