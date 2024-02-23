<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-transparent">
      <a class="navbar-brand" href="../views/HomeView.vue">
        <span class="logo">Kittleys</span>
      </a>
  
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
  
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav mx-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Admin</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
   
  }
  </script>
  
  <style scoped>
  /* Custom styling for the navbar */
  .navbar {
    background-color: transparent !important;
  }

  .logo{
    padding-left: 30px;
    font-size: 30px !important;
  }
  
  .navbar-brand .logo {
    font-family: 'Maven Pro', sans-serif;
    font-size: 1.5rem; /* Adjust the font size as needed */
    font-weight: bold; /* Adjust the font weight as needed */
    color: black !important; /* Set the font color to black */
  }
  
  .navbar-nav {
    font-family: 'Maven Pro', sans-serif;
  }
  
  .navbar-nav .nav-item .nav-link {
    color: black !important;
  }
  </style>
  