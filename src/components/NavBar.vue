<template>
  <nav :class="['container', isScrolled ? 'active' : 'isScrolled']">
      <div class="left">
  <div class="taps">
      <div class="tap">Home</div>
      <div class="tap">Product</div>
      <div class="tap">Pricing</div>
      <div class="tap">About</div>
      <div class="tap">Contact</div>
    </div>
    <div class="logo">
      <img src="../assets/logo.png" alt="Logo" />
    </div>
      </div>
  
    <div class="social">
      <img src="../assets/twitter.svg" alt="Logo" />
   
      <img src="../assets/face.svg" alt="Logo" />
         <img src="../assets/linkedin.svg" alt="Logo" />
    </div>
  </nav>
</template>

<script>
export default {
  data(){
    return{
      isScrolled:false
    }
  },
   mounted(){
      window.addEventListener('scroll', this.handleScroll);
    },
    methods:{
        handleScroll() {
      this.isScrolled = window.scrollY < 850;
    },
    }
};
</script>

<style>
body{
  position: relative;
}
.container {
  position: fixed;
  /* top:0;
  */
   transform: translate(-50%, 0); 
right: 50%;
left: 50%;
  width: 1210px;
  height: 140px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  z-index: 1000;

}
.left{
    display: flex;
    flex-direction: row;
}
.taps {
  display: inline-flex;
  align-items: center;
  gap: 24px;
}
.tap {
  color: var(--Light-text, #fff);
  text-align: center;

  font-family: Graphik;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: 28px;
  letter-spacing: 0.2px;
}
.logo {
  display: flex;
  padding: 20px;
  align-items: center;
  justify-content: center;
}
.logo img {
  padding-bottom: 10px;
}
.social{
    display: flex;
align-items: center;
gap: 24px;
}
.isScrolled{
width: 100%;
padding: 0px 240px;

  background: rgba(0, 0, 0, 0.2); 
  backdrop-filter: blur(10px);
  transition: background-color 0.5s ease, backdrop-filter 0.5s ease, padding 0.5s ease;
}
</style>
