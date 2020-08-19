<template>
  <div class="hello">
    <Header />
    <div class="dashboard">
        <h1>Simple Vue App served by NGINX and Docker</h1>
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from './Header.vue'
import Footer from './Footer.vue'

export default {
  name: 'SampleApp',
  components: {
    Header,
    Footer
  }
}
</script>
