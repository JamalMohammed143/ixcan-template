<script setup>
defineProps({
  title: String,
  content: String,
  image: String
})
</script>

<template>
  <section class="section">
    <div class="section-content">
      <div class="text-content">
        <h2>{{ title }}</h2>
        <p>{{ content }}</p>
      </div>
      <div class="image-content">
        <img :src="image" :alt="title">
      </div>
    </div>
  </section>
</template>

<style scoped>
.section {
  padding: 4rem 2rem;
  background: #f8f9fa;
}

.section-content {
  max-width: 1200px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
  align-items: center;
}

.text-content h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
  color: #2c3e50;
}

.text-content p {
  color: #666;
  line-height: 1.6;
}

.image-content img {
  width: 100%;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}
</style>