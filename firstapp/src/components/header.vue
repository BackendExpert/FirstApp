<!-- src/components/Header.vue -->
<template>
    <header class="header">
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
  </template>
  
  <script>
  export default {
    name: 'Header'
  }
  </script>
  
  <style scoped>
  .header {
    background-color: #333;
    padding: 1rem;
  }
  .header nav ul {
    list-style-type: none;
    display: flex;
    justify-content: space-around;
  }
  .header nav ul li a {
    color: white;
    text-decoration: none;
  }
  </style>
  