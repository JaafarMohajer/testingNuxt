<template>
    <div>
        <h1> About Us</h1>
    </div>
  
</template>

<script>
export default {
    name:'about',

    head() {
      return {
        title: 'About Page',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Nuxt Website Designing - About Page'
          },
          {
            hid: 'keywords',
            name: 'keywords',
            content: 'Vue, Nuxt, Javascript - About Page'
          }
          
        ]
      }
    }
}
</script>
