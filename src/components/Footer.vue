<template>
  <footer class="footer">
    <div class="footer-content">
      <div class="footer-section">
        <h3>IXCAN</h3>
        <p>Tata Memorial Hospital</p>
      </div>
      <div class="footer-section">
        <h3>Contact</h3>
        <p>info@ixcan.com</p>
      </div>
      <div class="footer-section">
        <h3>Follow Us</h3>
        <div class="social-links">
          <a href="#" target="_blank">LinkedIn</a>
          <a href="#" target="_blank">Twitter</a>
        </div>
      </div>
    </div>
    <div class="footer-bottom">
      <p>&copy; 2024 IXCAN. All rights reserved.</p>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  background: #2c3e50;
  color: white;
  padding: 3rem 2rem 1rem;
}

.footer-content {
  max-width: 1200px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 2rem;
}

.footer-section h3 {
  margin-bottom: 1rem;
  font-size: 1.2rem;
}

.social-links a {
  display: block;
  color: white;
  margin-bottom: 0.5rem;
}

.footer-bottom {
  margin-top: 2rem;
  padding-top: 1rem;
  text-align: center;
  border-top: 1px solid rgba(255,255,255,0.1);
}
</style>