<template>
  <section class="project-overview">
    <div class="content-wrapper">
      <div class="text-content">
        <h2>Empowering geriatric Oncologists to streamline assessments, reduce manual effort, and enhance geriatric patient care</h2>
        <div class="overview">
          <h3>Project Overview</h3>
          <p>We launched CareAlign, a cutting-edge digital assessment assistant designed to streamline the submission process and enhance data accuracy for healthcare providers and elderly patients. This application simplifies interactions and improves user experience within the healthcare system.</p>
        </div>
      </div>
      <div class="image-content">
        <img src="path-to-your-image.jpg" alt="Healthcare professional using CareAlign app">
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

.text-content h2 {
  font-size: 2.5rem;
  line-height: 1.2;
  margin-bottom: 2rem;
  color: #2c3e50;
  font-weight: bold;
}

.overview h3 {
  font-size: 1.5rem;
  color: #42b883;
  margin-bottom: 1rem;
}

.overview p {
  font-size: 1.1rem;
  line-height: 1.6;
  color: #666;
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

  .text-content h2 {
    font-size: 2rem;
  }
}
</style>