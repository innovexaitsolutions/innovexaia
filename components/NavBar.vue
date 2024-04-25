<template>
    <nav class="bg-gray-800 text-white py-4">
      <div class="container mx-auto flex justify-between items-center">
        <!-- Left side of the navbar -->
        <div>
          <!-- Your logo or brand name can go here -->
          <span class="text-xl font-bold">INNOVEXA</span>
        </div>
        
        <!-- Center of the navbar -->
        <div>
          <!-- Centered icon -->
          <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <!-- Your icon SVG code here -->
          </svg>
        </div>
        
        <!-- Right side of the navbar -->
        <div>
          <!-- Navbar links can go here -->
        </div>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'Navbar'
  }
  </script>
  
  <style scoped>
  /* Add any custom styles here */
  .container {
    max-width: 1500px;
    margin: 0 auto;
  }
  </style>
  