<template>
  <div class="home">
    <Header/>
    <router-view/>

  </div>

</template>

<script>

import Header from '@/components/Header/Header.vue'

export default {
  name: 'Home',
  components: {
    Header,
  }
}
</script>
