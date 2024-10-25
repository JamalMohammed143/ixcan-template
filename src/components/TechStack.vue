<template>
  <section class="tech-stack">
    <div class="tech-stack-content">
      <div class="project-info">
        <h2>Project Details</h2>
        <div class="timeline">
          <h3>Project Timeline</h3>
          <p>Aug 2023 - Ongoing</p>
        </div>
        <div class="services">
          <h3>Services Provided</h3>
          <p>UX, Dev, QA, DevOps</p>
        </div>
      </div>
      
      <div class="stack">
        <h2>Technology Stack</h2>
        <div class="stack-categories">
          <div class="stack-category">
            <h3>Front-End</h3>
            <ul>
              <li>NextJS</li>
              <li>Chakra UI</li>
            </ul>
          </div>
          <div class="stack-category">
            <h3>Back-End</h3>
            <ul>
              <li>NestJS</li>
              <li>TypeORM</li>
            </ul>
          </div>
          <div class="stack-category">
            <h3>Database</h3>
            <ul>
              <li>MYSQL</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.tech-stack {
  padding: 4rem 2rem;
  background: white;
}

.tech-stack-content {
  max-width: 1200px;
  margin: 0 auto;
}

h2 {
  font-size: 2rem;
  margin-bottom: 2rem;
  color: #2c3e50;
}

h3 {
  font-size: 1.2rem;
  color: #42b883;
  margin-bottom: 1rem;
}

.project-info {
  margin-bottom: 3rem;
}

.timeline, .services {
  margin-bottom: 2rem;
}

.stack-categories {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
}

.stack-category ul {
  list-style: none;
  padding: 0;
}

.stack-category li {
  padding: 0.5rem 0;
  color: #666;
}
</style>