<template>
  <div>
    <HeroSection />
    <AboutSection />
    <VideosSection />
    <JoinUsSection />
  </div>
</template>

<script>
import HeroSection from '../components/sections/Hero';
import AboutSection from '../components/sections/About';
import VideosSection from '../components/sections/Videos';
import JoinUsSection from '../components/sections/JoinUs';

export default {
  components: {
    HeroSection,
    AboutSection,
    VideosSection,
    JoinUsSection
  }
}
</script>

<style>

</style>
