<template>
  <div>
    <Header />
    <nuxt />
    <Footer />
  </div>
</template>
<script type='text/javascript'>
import Header from '../components/common/Header'
import Footer from '../components/common/Footer'
export default {
  components: {
    Header, Footer
  }
}
</script>
