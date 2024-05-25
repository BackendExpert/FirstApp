<!-- src/components/Hero.vue -->
<template>
    <section class="hero">
      <h1>Welcome to Our Landing Page</h1>
      <p>Your journey to success starts here.</p>
      <button>Get Started</button>
    </section>
  </template>
  
  <script>
  export default {
    name: 'AppHero'
  }
  </script>
  
  <style scoped>
  .hero {
    text-align: center;
    padding: 2rem;
    background: #f4f4f4;
  }
  .hero h1 {
    font-size: 2.5rem;
  }
  .hero p {
    font-size: 1.2rem;
    margin: 1rem 0;
  }
  .hero button {
    padding: 0.5rem 1rem;
    font-size: 1rem;
    cursor: pointer;
  }
  </style>
  