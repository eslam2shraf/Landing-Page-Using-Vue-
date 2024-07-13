<template>
  <div class="featuers-container">
    <div class="fetures-info">
      <h1>Features</h1>
      <p>
        Most calendars are designed for teams. <br />
        Slate is designed for freelancers
      </p>
    </div>
    <div class="features-details">
      <div class="details-item">
        <img src="../assets/shapes.svg" alt="shapes" />
        <h3>OpenType features Variable fonts</h3>
        <p>
          Slate helps you see how many more days you need to work to reach your
          financial goal.
        </p>
      </div>
      <div class="details-item">
        <img src="../assets/drow.svg" alt="shapes" width="61px" height="61px" />
        <h3>Design with real data</h3>
        <p>
          Slate helps you see how many more days you need to work to reach your
          financial goal.
        </p>
      </div>
      <div class="details-item">
        <img src="../assets/brush.svg" alt="shapes" />
        <h3>Fastest way to take action</h3>
        <p>
          Slate helps you see how many more days you need to work to reach your
          financial goal.
        </p>
      </div>
    </div>
    <div class="features-video">
      <img src="../assets/screenvideo.png" alt="video" />
      <button>
        <img src="../assets/play.svg" alt="playbutton" />
      </button>
    </div>
    <div class="organize">
      <div class="organize-left">
          <div class="left-text">
     <h2>Fastest way to<br/> organize</h2>
        <p>
          Most calendars are designed for teams.<br/> Slate is designed for
          freelancers
        </p>

          </div>
   
        <button>Try For Free</button>
      </div>
      <div class="organize-right">
        <img src="../assets/Macbook.png" alt="" />
      </div>
    </div>
    <div class="feedback">
     <div class="letter-image">
         <img src="../assets/letter.png" alt="feedback">
     </div>
      <div class="feedback-right">
          <div class="right-text">
              <div class="form-head">
<h2>At your fingertips</h2>
<p>Lightning fast 
prototyping </p>

              </div>

          </div>
          <div class="right-form">
              <h3>Subscribe to our Newsletter</h3>
              <p>Available exclusivery on Figmaland</p>
              <div class="form">
                      <input type="text" value="Your Email">
              <button>Subscribe</button>
              </div>
          
               </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.featuers-container {
  padding-top: 80px;
  margin: 0px;
  /* width: 100vw; */
  /* margin-top:80px; */
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 80px;
  align-self: stretch;
}
.fetures-info {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 7px;
}
.fetures-info h1 {
  color: var(--text, #252b42);
  text-align: center;

  /* H2 */
  font-family: Graphik;
  font-size: 48px;
  font-style: normal;
  font-weight: 400;
  line-height: 55px; /* 114.583% */
  letter-spacing: 0.2px;
}
.fetures-info p {
  color: var(--second-text, #374754);
  text-align: center;
  margin: 0px;
  /* H4 */
  font-family: Graphik;
  font-size: 28px;
  font-style: normal;
  font-weight: 400;
  line-height: 40px; /* 142.857% */
  letter-spacing: 0.2px;
}
.features-details {
  /* width: 50%; */
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  gap: 52px;
}
.details-item {
  display: flex;
  width: 255px;
  flex-direction: column;
  align-items: center;
  gap: 5px;
}
.details-item h3 {
  color: var(--text, #252b42);
  text-align: center;
  display: flex;
  padding: 10px;
  align-items: center;
  gap: 10px;
  /* H3 */
  font-family: Graphik;
  font-size: 20px;
  font-style: normal;
  font-weight: 700;
  line-height: 28px; /* 140% */
  letter-spacing: 0.1px;
}
.details-item p {
  margin: 0px;
  color: var(--second-text, #374754);
  text-align: center;
  display: flex;
  padding: 0px 10px;
  align-items: center;
  gap: 10px;
  /* Paragraphe */
  font-family: Graphik;
  font-size: 18px;
  font-style: normal;
  font-weight: 400;
  line-height: 25px; /* 138.889% */
  letter-spacing: 0.2px;
}
.features-video {
  flex-shrink: 0;
  border-radius: 81.477px;
  position: relative;
}
.features-video button {
  width: 187.397px;
  height: 187.397px;
  flex-shrink: 0;
  background-color: #2091f9;
  border-radius: 50%;

  position: absolute;
  top: 50%;
  left: 50%;
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  border: none;
  cursor: pointer;
}
.organize {
  display: flex;
  padding: 43px 0px;
  align-items: center;
  gap: 50px;
}
.organize-left {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 60px;
}
.left-text{
    display: flex;
flex-direction: column;
align-items: flex-start;
gap: 7px;
}
.organize-left h2{
    color: var(--text, #252B42);

/* H2 */
font-family: Graphik;
font-size: 48px;
font-style: normal;
font-weight: 400;
line-height: 55px; /* 114.583% */
letter-spacing: 0.2px;
}
.organize-left p {
    color: var(--second-text, #374754);
display: flex;
padding: 10px 0px;
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
.organize-left button{
    display: flex;
width: 236px;
padding: 16px 0px;
flex-direction: column;
align-items: center;
border-radius: 35px;
background: var(--Primary, #2091F9);
color: var(--Light-text, #FFF);
outline: none;
border: none;
cursor: pointer;

font-family: Graphik;
font-size: 20px;
font-style: normal;
font-weight: 700;
line-height: 28px; /* 140% */
letter-spacing: 0.1px;
}
.feedback{
    display: flex;
height: 638px;
padding: 0px 50px;
align-items: flex-start;
gap: 50px;
margin-top:150px ;
}
.feedback-right{
    display: flex;
width: 544px;
padding: 0px 63px;
flex-direction: column;
align-items: flex-start;
gap: 15px;
}
.form-head{
    display: flex;
flex-direction: column;
align-items: flex-start;
gap: 7px;
}
.form-head h2{
color: var(--text, #252B42);

/* H3 */
font-family: Graphik;
font-size: 20px;
font-style: normal;
font-weight: 700;
line-height: 28px; /* 140% */
letter-spacing: 0.1px;
}
.form-head p{
color: var(--text, #252B42);

/* H2 */
font-family: Graphik;
font-size: 48px;
font-style: normal;
font-weight: 400;
line-height: 55px; /* 114.583% */
letter-spacing: 0.2px;
}
.right-form{
    display: flex;
padding: 10px;
flex-direction: column;
align-items: flex-start;
}
.right-form h3{
    color: var(--text, #252B42);

/* H3 */
font-family: Graphik;
font-size: 20px;
font-style: normal;
font-weight: 700;
line-height: 28px; /* 140% */
letter-spacing: 0.1px;
}
.right-form p{
    color: var(--second-text, #374754);

/* Paragraphe */
font-family: Graphik;
font-size: 18px;
font-style: normal;
font-weight: 400;
line-height: 25px; /* 138.889% */
letter-spacing: 0.2px;
}
.form{
    display: flex;
padding: 34px 0px;
align-items: center;
gap: 12px;
}
.form input{
display: flex;
width: 273px;
padding: 19px 39px;
flex-direction: column;
align-items: flex-start;
gap: 64px;
border-radius: 39px;
border: 1px solid #E8E8E8;
background: #F4F4F4;border-radius: 39px;
border: 1px solid #E8E8E8;
background: #F4F4F4;
outline: none   ;
}
.form button{
display: flex;
padding: 19px 38px;
flex-direction: column;
align-items: center;
gap: 10px;
border-radius: 35px;
background: var(--Primary, #2091F9);
font-family: Graphik;
font-size: 20px;
font-style: normal;
font-weight: 400;
line-height: 20px; /* 100% */
letter-spacing: 0.2px;
color: var(--Light-text, #FFF);
outline: none;
border :none;
cursor: pointer;
}
</style>

