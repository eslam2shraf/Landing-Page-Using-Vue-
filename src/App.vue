<template>
<NavBar/>
<FirstSection/>
<Features/>
<Partners/>
<Testimonials/>
<Pricing/>
<ContactUs/>
<Footer/>
</template>

<script>
import NavBar from './components/NavBar.vue'
import FirstSection from './components/FirstSection.vue'
import Features from './components/Features.vue'
import Partners from './components/Partners.vue'
import Testimonials from './components/Testimonials.vue'
import Pricing from './components/Pricing.vue'
import ContactUs from './components/ContactUs.vue'
import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components: {
   NavBar,
   FirstSection,
   Features,
   Partners,
   Testimonials,
   Pricing,
   ContactUs,
   Footer

  }
}
</script>

<style>
/* #app{
  margin: 0px;
  padding: 0px;
  width: 100vw;
  
} */
*{

margin: 0px;
padding: 0px;
box-sizing: border-box;
}
</style>
