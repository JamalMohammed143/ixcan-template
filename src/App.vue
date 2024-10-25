<script setup>
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import ProjectOverview from './components/ProjectOverview.vue'
import Section from './components/Section.vue'
import TechStack from './components/TechStack.vue'
import Footer from './components/Footer.vue'

const section1Data = {
  title: "Digital Healthcare Innovation",
  content: "At Tata Memorial Hospital, we're revolutionizing geriatric care through digital transformation. Our comprehensive assessment platform streamlines the evaluation process, ensuring efficient and accurate patient care delivery.",
  image: "https://images.unsplash.com/photo-1576091160399-112ba8d25d1d?ixlib=rb-1.2.1&auto=format&fit=crop&w=2850&q=80"
}
</script>

<template>
  <div class="app-container">
    <Header />
    <main>
      <Hero />
      <ProjectOverview />
      <Section 
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
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

main {
  flex: 1;
}
</style>