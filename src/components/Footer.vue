<template>
  <footer>
      <div class="footer-container">
    <div class="footer-left">
      <div class="pages">
        <div class="pages-header">
          <div class="header-content">
            <h3>Pages</h3>
          </div>
          <div class="pages-list">
            <ul>
              <li>Home</li>
              <li>Product</li>
              <li>Pricing</li>
              <li>About</li>
              <li>Contact</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="pages">
        <div class="pages-header">
          <div class="header-content">
            <h3>Tomothy </h3>
          </div>
          <div class="pages-list">
            <ul>
              <li>Eleanor Edwards</li>
              <li>Ted Robertson</li>
              <li>Annette Russell   </li>
              <li>Jennie Mckinney</li>
              <li>Gloria Richards</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="pages">
        <div class="pages-header">
          <div class="header-content">
            <h3>Jane Black</h3>
          </div>
          <div class="pages-list">
            <ul>
              <li>Philip Jones</li>
              <li>Product</li>
              <li>Colleen Russell</li>
              <li>Marvin Hawkins</li>
              <li>Bruce Simmmons</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="footer-right">
      <div class="contact-footer">
        <img src="../assets/mapwhite.svg" alt="map" />
        <p>7480 Mockingbird Hill undefined </p>
      </div>
         <div class="contact-footer">

          <img src="../assets/mobwhite.svg" alt="map">
          <p>(239) 555-0108</p>
      </div>
      <div class="social-footer">
           <img src="../assets/twitter.svg" alt="Logo" />
   
      <img src="../assets/face.svg" alt="Logo" />
         <img src="../assets/linkedin.svg" alt="Logo" />
      </div>
    </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style>

footer{
background: var(--Dark-background, #252B42);
    display: flex;
padding: 150px 0px;
flex-direction: column;
align-items: center;
align-self: stretch;
}
.footer-container{
    display: flex;
    flex-direction: row;
align-items: flex-start;
gap: 125px;
}
.footer-left{
    display: flex;
align-items: center;
flex-direction: row;
gap: 20px;
}
.pages{
    display: flex;
width: 170px;
flex-direction: column;
align-items: flex-start;
gap: 15px;
}
.pages-header{
    display: flex;
width: 186px;
flex-direction: column;
align-items: flex-start;
gap: 15px;
}
.header-content h3{
    display: flex;
padding: 10px 0px;
align-items: center;
gap: 10px;
color: var(--Light-text, #FFF);

font-family: Graphik;
font-size: 20px;
font-style: normal;
font-weight: 700;
line-height: 28px; 
letter-spacing: 0.1px;
}
.pages-list ul{
    list-style: none;
    display: flex;
flex-direction: column;
align-items: flex-start;
gap: 16px;
}
.pages-list li{
    color: var(--Light-text, #FFF);
display: flex;
align-items: center;
gap: 10px;

font-family: Graphik;
font-size: 15px;
font-style: normal;
font-weight: 400;
line-height: 28px; 
letter-spacing: 0.2px;
}
.footer-right{
    display: flex;
flex-direction: column;
align-items: flex-start;
gap: 10px;
}
.contact-footer{
    display: flex;
align-items: center;
}
.contact-footer p{
    display: flex;
padding: 0px 8px;
align-items: center;
color: var(--Light-text, #FFF);

/* Link */

font-family: Graphik;
font-size: 15px;
font-style: normal;
font-weight: 400;
line-height: 27px; /* 180% */
letter-spacing: 0.2px;
}
.contact-footer img{
    width: 35px;
height: 35px;

}
.social-footer{
display: flex;
padding: 20px 0px;
align-items: center;
gap: 24px;
}
</style>
