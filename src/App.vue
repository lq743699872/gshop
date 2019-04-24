<template>
  <div>
    <router-view/>
    <FooterGuide>

    </FooterGuide>
  </div>
</template>

<script>
  import FooterGuide from './components/FooterGuide/FooterGuide.vue'

  export default {
    components: {
      FooterGuide
    },
    methods:{

    },

  }
</script>

<style>

</style>
