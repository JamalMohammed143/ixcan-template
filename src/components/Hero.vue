<template>
  <section class="hero">
    <div class="hero-overlay"></div>
    <div class="hero-content">
      <h1>Simplifying Healthcare Assessments with Digital Efficiency</h1>
    </div>
    <div class="hero-image">
      <img src="https://i.imgur.com/YourImageURL.jpg" alt="Healthcare Assessment Interface">
    </div>
  </section>
</template>

<style scoped>
.hero {
  position: relative;
  height: 80vh;
  background: #f8f9fa;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
}

.hero-overlay {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: rgba(44, 62, 80, 0.7);
  z-index: 1;
}

.hero-content {
  position: relative;
  z-index: 2;
  color: white;
  text-align: center;
  max-width: 800px;
  padding: 0 2rem;
}

.hero-content h1 {
  font-size: 3rem;
  font-weight: bold;
  margin-bottom: 1rem;
  line-height: 1.2;
}

.hero-image {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 0;
}

.hero-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center;
}

@media (max-width: 768px) {
  .hero-content h1 {
    font-size: 2rem;
  }
}
</style>