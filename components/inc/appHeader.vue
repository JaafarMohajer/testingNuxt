<template>
    <div>
        <nav class="navbar navbar-expand-lg navbar-light bg-white shadow">
  <div class="container">
    <a class="navbar-brand" href="#">
      <img src="/images/logo-varnish.svg" class="logo-img" alt="">
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <NuxtLink to="/" class="nav-link">Home</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink to="/about" class="nav-link">About</NuxtLink>
          
        </li>
        <li class="nav-item">
          <NuxtLink to="/services" class="nav-link">Services</NuxtLink>
          
        </li>
        <li class="nav-item">
          <NuxtLink to="/contact" class="nav-link">Contact</NuxtLink>
          
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled">Disabled</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
    </div>
  
</template>

<script>
export default {
    name: 'appHeader'

}
</script>

<style>
.logo-img{
  width: 170px;
}
</style>
