<script setup lang="ts">

</script>
<template>
    <div>
      <nav id="sidebarMenu" class="sidebar col-md-3 col-lg-2 d-md-block collapse ">
        <div class="position-sticky pt-3">
          <ul class="nav flex-column">
            <li class="nav-item" style="margin-top: 100px;">
              <router-link to="/dashboard" class="nav-link">Dashboard</router-link>
            </li>
            <li class="nav-item">
              
              <router-link to="/profile" class="nav-link">Product</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/settings" class="nav-link">Category</router-link>
            </li>
          </ul>

        </div>
      </nav>
    </div>

</template>

<style>
.sidebar {
  width: 250px;
  position: fixed;
  top: 0;
  left: 0;
  bottom: 0;
  background-color: #343a40; /* Warna latar belakang sidebar */
  color: #fff; /* Warna teks */
}

.sidebar-nav {
  padding-top: 20px;
}

.nav-link {
  color: #fff; /* Warna teks untuk link */
}

.nav-link:hover {
  color: #ccc; /* Warna teks saat dihover */
}
</style>