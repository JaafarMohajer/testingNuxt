<template>
    <div>
      <appHeader />
      <Nuxt />
      <appFooter />
    </div>
  </template>

  <script>
    
    import appHeader from '~/components/inc/appHeader.vue';
    import appFooter from '~/components/inc/appFooter.vue';

    export default{
        name: 'default',
        components: {
            appHeader,
            appFooter,
        }
    }

  </script>
  