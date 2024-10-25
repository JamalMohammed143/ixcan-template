<script setup>
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import ProjectOverview from './components/ProjectOverview.vue'
import Section from './components/Section.vue'
import TechStack from './components/TechStack.vue'
import Footer from './components/Footer.vue'

const section1Data = {
  title: "Project Overview",
  content: "We launched CareAlign, a cutting-edge digital assessment assistant designed to streamline the submission process and enhance data accuracy for healthcare providers and elderly patients. This application simplifies interactions and improves user experience within the healthcare system.",
  image: "/images/IXCAN-Overview.webp"
}
const section2Data = {
  title: "Key solution and results",
  content: "CareAlign dramatically reduced the administrative load on healthcare providers and optimized operations at Tata Memorial Hospital. By minimizing paperwork and boosting data accuracy, the platform achieved high satisfaction rates among doctors and elderly patients, leading to a notable improvement in the quality of patient care.",
  image: "/images/IXCAN-Protoype.webp"
}
</script>

<template>
  <div class="app-container">
    <Header />
    <main>
      <Hero />
      <div class="section-main-title">
        <h2>Empowering geriatric Oncologists to streamline assessments, reduce manual effort, and enhance geriatric patient care</h2>
      </div>
      <ProjectOverview
        :title="section1Data.title"
        :content="section1Data.content"
        :image="section1Data.image"
         />
         <div class="section-main-title">
        <h2>CareAlign has significantly improved the operational efficiency of geriatric oncologists by reducing paperwork and enhancing data accuracy, leading to better patient care.</h2>
      </div>
      <ProjectOverview
        :title="section1Data.title"
        :content="section1Data.content"
        :image="section1Data.image"
         />
      <TechStack />
    </main>
    <Footer />
  </div>
</template>

<style>
.app-container { 
  background: #f8f9fa;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

main {
  flex: 1;
}

.section-main-title {
  max-width: 1200px;
  margin: 0 auto;
  align-items: center;
  padding: 6rem 2rem;
}

.section-main-title h2 {
  font-size: 2rem;
}
</style>