<template>
<div class="partners">

  <div class="part-header">
      <h1>Partners</h1>
      <p>Most calendars are designed for teams. <br/>
Slate is designed for freelancers</p>
  </div>
  <div class="clients">
      <div class="clients-row">
   <Client>
       <p>Client Name</p>
       <img src="../assets/google.svg" alt="google">
   </Client>
       <Client>
       <p>Client Name</p>
       <img src="../assets/amazon.png" alt="amazon">
   </Client>  
    <Client>
       <p>Client Name</p>
       <img src="../assets/soft.png" alt="microsoft">
   </Client>  
    <Client>
       <p>Client Name</p>
       <img src="../assets/uber.png" alt="uber">
   </Client>

      </div>

 <div class="clients-row">
   <Client>
       <p>Client Name</p>
       <img src="../assets/drop.png" alt="dropbox" width="180" height="40px">
   </Client>
       <Client>
       <p>Client Name</p>
       <img src="../assets/google.svg" alt="google">
   </Client>  
    <Client>
       <p>Client Name</p>
       <img src="../assets/uber.png" alt="uber">
   </Client>  
    <Client>
       <p>Client Name</p>
       <img src="../assets/amazon.png" alt="amazon" >
   </Client>

      </div>





  </div>
  <div class="part-button">
      <button>Try For Free</button>
  </div>

</div>
</template>

<script>
import Client from'./Client.vue'
export default {
components:{
    Client
}
}
</script>

<style>
.partners{
    display: flex;
padding: 80px 0px;
flex-direction: column;
align-items: center;
gap: 80px;
align-self: stretch;
}
.clients-row{
    display: flex;
align-items: center;
}
.part-header{
    display: flex;
flex-direction: column;
align-items: center;
gap: 7px;
}
.part-header h1{
    display: flex;
padding: 10px;
align-items: center;
gap: 10px;
color: var(--text, #252B42);
text-align: center;

/* H2 */
font-family: Graphik;
font-size: 48px;
font-style: normal;
font-weight: 400;
line-height: 55px; /* 114.583% */
letter-spacing: 0.2px;
}
.part-header p{
    color: var(--second-text, #374754);
text-align: center;
display: flex;
padding: 10px;
align-items: center;
gap: 10px;
/* H4 */
font-family: Graphik;
font-size: 28px;
font-style: normal;
font-weight: 400;
line-height: 40px; /* 142.857% */
letter-spacing: 0.2px;
}
.part-button button{
display: flex;
width: 236px;
padding: 16px 0px;
flex-direction: column;
align-items: center;
border-radius: 35px;
background: var(--Primary, #2091F9);
color: var(--Light-text, #FFF);
border:none;
cursor: pointer;
font-family: Graphik;
font-size: 20px;
font-style: normal;
font-weight: 700;
line-height: 28px; /* 140% */
letter-spacing: 0.1px;
}
</style>