<template>
    <nav class="bg-gray-800 text-white py-4">
      <div class="container mx-auto flex justify-between items-center">
        <!-- Left side of the navbar -->
        <div class="logo-cont">
          <!-- Your logo or brand name can go here -->
          <img src="/public/image/index/logo.png" alt="Logo" class="logo" />
        </div>
        
        <!-- Center of the navbar -->
        <div>
          <!-- Centered icon -->
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
  name: 'NavBar'
}
</script>
  
<style scoped>
/* Add any custom styles here */
.container {
  max-width: 78.125vw;;
  margin: 0 auto;
}

.logo{
  width: 20%;
  height: 100%;
  object-fit: contain;
}

@media screen and (max-width: 767px) {
  .logo{
    width: 50%;
  }

  .logo-cont{
    width: 100%;
    display: flex;
    justify-content: center;
  }
}

@media (min-width: 768px) and (max-width: 1023px) {
  .logo{
    width: 30%;
  }

  .logo-cont{
    width: 100%;
    display: flex;
    justify-content: center;
  }
}
</style>
  