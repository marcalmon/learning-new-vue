<template>
  <div class="page">
    <Navbar></Navbar>
    <Header></Header>
    <Services></Services>
    <Portfolio></Portfolio>
   
    
  </div>
</template>

<script>
import Navbar from 'components/Navbar'
import Header from 'components/Header'
import Services from 'components/Services'
import Portfolio from 'components/Portfolio'

export default {
  components: {
    Navbar,
    Header,
    Services,
    Portfolio
  }
}
</script>
