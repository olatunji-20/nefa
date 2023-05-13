<template>
  <Navbar />
  <Footbar />
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import Footbar from '@/components/Footbar.vue'


export default {
  name: 'HomeView',
  components: {
    Navbar,
    Footbar
  }
}
</script>
