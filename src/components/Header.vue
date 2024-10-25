<script setup>
const logo = "IXCAN"
</script>

<template>
  <header class="header">
    <div class="header-content">
      <h1 class="logo">{{ logo }}</h1>
      <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>
</template>

<style scoped>
.header {
  background: white;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  padding: 1rem 0;
}

.header-content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
  color: #2c3e50;
}

nav a {
  margin-left: 2rem;
  color: #2c3e50;
  text-decoration: none;
}

nav a:hover {
  color: #42b883;
}
</style>