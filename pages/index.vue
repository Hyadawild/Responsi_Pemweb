<template>
  <div>
    <NavSection />
    <HeroSection />
    <AboutSection />
    <ProjectsSection />
    <ContactSection />
    <FooterSection/>
  </div>
</template>

<script>
import NavSection from '~/components/NavSection.vue'
import HeroSection from '~/components/HeroSection.vue';
import AboutSection from '~/components/AboutSection.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';
import FooterSection from '~/components/FooterSection.vue'; 

export default {
  components: {
    NavSection,HeroSection,AboutSection,ProjectsSection,ContactSection,FooterSection
  }
}
</script>./Index.vue
