<script setup lang="ts">
import SessionOne from '@/components/SessionOne/index.vue'
import AboutUs from '@/components/AboutUs/index.vue'
import AvailableSession from '@/components/AvailableSession/index.vue'
import RegisterSection from '@/components/FromSection/RegisterSection.vue';
</script>

<template>
  <main class="bg-backgroundColorMain">
    <HeaderComponent/>
    <SessionOne />
    <AvailableSession />
    <AboutUs />
    <RegisterSection/>
    <FooterComponent/>
  </main>
</template>
