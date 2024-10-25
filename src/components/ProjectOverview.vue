<script setup>
defineProps({
  title: String,
  content: String,
  image: String
})
</script>


<template>
  <section class="project-overview">
    <div class="content-wrapper">
      <div class="text-content">
        <div class="overview">
          <h3>{{ title }}</h3>
          <p>{{ content }}</p>
        </div>
      </div>
      <div class="image-content">
        <img :src="image" :alt="title">
      </div>
    </div>
  </section>
</template>

<style scoped>
.project-overview {
  padding: 6rem 2rem;
  background: #f8f9fa;
}

.content-wrapper {
  max-width: 1200px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
  align-items: center;
}

.overview h3 {
  font-size: 2rem;
  margin-bottom: 1rem;
  color: #2c3e50;
}

.overview p {
  color: #2c3e50;
  line-height: 1.6;
}

.image-content img {
  width: 100%;
  border-radius: 12px;
  box-shadow: 0 8px 16px rgba(0,0,0,0.1);
}

@media (max-width: 768px) {
  .content-wrapper {
    grid-template-columns: 1fr;
  }
}
</style>