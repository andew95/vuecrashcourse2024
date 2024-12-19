<script setup>
import Hero from './components/Hero.vue';
import Navbar from './components/Navbar.vue';
import HomeCards from './components/HomeCards.vue'
import JobListings from './components/JobListings.vue'
</script>
<template>
  <Navbar />
  <Hero title="Apiwut" />
  <HomeCards />
  <JobListings :limit="3" />
</template>