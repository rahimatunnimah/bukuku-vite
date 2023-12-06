<script setup lang="ts">

</script>

<template>
  <header class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
       <i class="fas fa-home"></i>
      <a class="navbar-brand m-3" href="#">BUKUKU</a>
      <button 
        class="navbar-toggler" 
        type="button" 
        data-bs-toggle="collapse" 
        data-bs-target="#sidebarMenu" 
        aria-controls="sidebarMenu" 
        aria-expanded="false"
        aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <input class="form-control me-2 w-100" type="search" placeholder="Search" aria-label="Search" style="margin-left: 50px;">
      <button class="btn btn-outline-light" type="submit">Search</button>
    <div class="nav-item dropdown" style="margin-left: 70px;">
      <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
        Login
      </a>
      <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
        <li><a class="dropdown-item" href="#">Sign Up</a></li>
        <li><a class="dropdown-item" href="#">Login</a></li>
      </ul>
    </div>
    </div>
  </header>

</template>

<style scoped>
 
</style>
