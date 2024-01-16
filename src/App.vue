<template>
  <div class="wrapper" id="app">
    <div class="content-wrapper">
      <div class="container">
        <Header></Header>
        <Navbar />
      </div>
    </div>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Navbar from '@/components/Navbar.vue'

export default {
  // name: 'App',
  components: {
    Header,
    Navbar,
  }
}
</script>

<style></style>
