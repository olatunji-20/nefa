<template>
  <Navbar />
  <Collections />
  <Explore />
  <Footbar />
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import Collections from '@/components/Collections.vue'
import Explore from '@/components/Explore.vue'
import Footbar from '@/components/Footbar.vue'


export default {
  name: 'HomeView',
  components: {
    Navbar,
    Collections,
    Explore,
    Footbar
  }
}
</script>
