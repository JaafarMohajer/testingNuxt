<template>
  
  <div>

    <slider />

<div class="py-5 container"> 
  <div class="row">
    <div class="col-md-12 text center">
      <h1 class="main-heading" align="center">About Us</h1>
      <div class="underline mx-auto"></div>
      <p>
        "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna
         aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
         Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
      </p>
    </div>
  </div>
</div>

<div class="py-5 bg-gray">
  <div class="container">
    <div class="row">

      <div class="col-md-12 text center">
      <h1 class="main-heading" align="center">Our Services</h1>
      <div class="underline mx-auto"></div>

      <div class="col-md-4">
        <div class="box-card">
          <img src="/images/logo-varnish.svg" class="w-100" alt="Web Desiging">
          <div class="box-card-body">
          <h3 class="box-card-heading">Nuxt Designing</h3>
          <div class="undeline"></div>
          <p>
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna
         aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
         Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
          </p>

          </div>
        </div>
</div>
<div class="col-md-4">
        <div class="box-card">
          <img src="/images/logo-varnish.svg" class="w-100" alt="Web Desiging">
          <div class="box-card-body">
          <h3 class="box-card-heading">Web Development</h3>
          <div class="undeline"></div>
          <p>
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna
         aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
         Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
          </p>

          </div>
        </div>
</div>
<div class="col-md-4">
        <div class="box-card">
          <img src="/images/logo-varnish.svg" class="w-100" alt="Web Desiging">
          <div class="box-card-body">
          <h3 class="box-card-heading">SEO</h3>
          <div class="undeline"></div>
          <p>
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna
         aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
         Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
          </p>

          </div>
        </div>
</div>
      </div>
</div>
</div>
</div>
</div>
</template>

<script>

import slider from '~/components/slider.vue';

export default{
  name: 'IndexPage ',
  components :{ slider },

  head() {
      return {
        title: 'Home Page',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Nuxt Website Designing - Home Page'
          },
          {
            hid: 'keywords',
            name: 'keywords',
            content: 'Vue, Nuxt, Javascript - Home Page'
          }
          
        ]
      }
    }
}
</script>
