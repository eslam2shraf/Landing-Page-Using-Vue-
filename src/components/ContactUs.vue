<template>
  <div class="contact-us">
    <div class="contact-header">
      <h2>Contact Us</h2>
      <h4>Most calendars are designed for teams. <br />
        Slate is designed for freelancers</h4>
    </div>
    <div class="contact-content">
      <div class="contact-form">
        <h3>Contact Us</h3>
        <form @submit.prevent="sendMessage">
          <input type="text" placeholder="Your Name" v-model="name" required />
          <input type="email" placeholder="Your Email" v-model="email" required />
          <textarea placeholder="Your Message" v-model="message" required></textarea>
          <div class="form-button"><button type="submit">Send</button></div>
        </form>
      </div>
      <div class="contact-info">

          <div class="contact-items">
          <div class="cotact-info-item">
     <img src="../assets/map.svg" alt="map">
        <h5> 6386 Spring St undefined Anchorage, Georgia 12473 United States</h5>
          </div>
            <div class="cotact-info-item">
        <img src="../assets/phone.svg" alt="map">
        <h5> (843)5550130</h5>
          </div>
      <div class="cotact-info-item">
         <img src="../assets/mail.svg" alt="map">
        <h5> willie.jennings@example.com</h5>
          </div>
    </div>
   
        <div class="map">
  
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.0863170086487!2d-122.41941508468113!3d37.774929279758525!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80858064b981e5b3%3A0x4c34c0c7b3b70b21!2sCivic%20Center!5e0!3m2!1sen!2sus!4v1625292000000!5m2!1sen!2sus"
            width="600"
            height="450"
            style="border:0;"
            allowfullscreen=""
            loading="lazy"></iframe>
        </div>
        <div class="social-icons">
    <img src="../assets/twitterFiled.svg" alt="Logo" />
   
      <img src="../assets/faceFilled.svg" alt="Logo" />
         <img src="../assets/linkedFilled.svg" alt="Logo" />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      name: '',
      email: '',
      message: ''
    }
  },
  methods: {
    sendMessage() {
      alert(`Message sent by ${this.name}`);
      this.name = '';
      this.email = '';
      this.message = '';
    }
  }
};
</script>
<style scoped>
.contact-us {
display: flex;
padding: 50px 0px;
flex-direction: column;
align-items: center;
gap: 50px;
}

.contact-header {
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
gap: 16px;
margin-bottom: 20px;
}

.contact-header h2 {
color: var(--text, #252B42);
text-align: center;
font-family: Graphik;
font-size: 48px;
font-style: normal;
font-weight: 400;
line-height: 55px; /* 114.583% */
letter-spacing: 0.2px;
}

.contact-header h4 {
color: var(--second-text, #374754);
text-align: center;

/* H4 */
font-family: Graphik;
font-size: 28px;
font-style: normal;
font-weight: 400;
line-height: 40px; /* 142.857% */
letter-spacing: 0.2px;
}

.contact-content {
  display: flex;
  justify-content: space-around;
}

.contact-form {
 display: flex;
width: 453px;
flex-direction: column;
align-items: center;
padding: 52px 50px;
gap: 45px;
align-self: stretch;
border-radius: 20px;
border: 1px solid #DDD;
background: #FFF;

/* SHADOW */
box-shadow: 0px 13px 19px 0px rgba(0, 0, 0, 0.07);
}
.contact-form form{
    display: flex;
    flex-direction: column;
    align-items: center;
    gap:45px;
    width:100%
}

.contact-form h3 {
  font-size: 24px;
  /* margin-bottom: 15px; */
  color: var(--text, #252B42);
text-align: center;
/* H3 */
font-family: Graphik;
font-size: 20px;
font-style: normal;
font-weight: 700;
line-height: 28px; /* 140% */
letter-spacing: 0.1px;
}

.contact-form input,
.contact-form textarea {
display: flex;
padding: 19px 20px;
flex-direction: column;
align-items: flex-start;
gap: 47px;
align-self: stretch;
border-radius: 39px;
border: 1px solid #E8E8E8;
background: #F5F5F5;
color: var(--Background, #030011);
font-family: Graphik;
font-size: 15px;
font-style: normal;
font-weight: 400;
line-height: 16px; /* 106.667% */
letter-spacing: 0.1px;
}
.contact-form textarea{
 display: flex;
height: 147px;
padding: 19px 216px 131px 19px;
align-items: center;
align-self: stretch;
border: 1px solid #E8E8E8;
background: #F5F5F5;
border-radius: 5px;
overflow: hidden;
}
.form-button{
    width: 100%;
    display: flex;
    justify-content: flex-start;
}
.contact-form button {
display: flex;
width: 145px;
padding: 18px 38px;
flex-direction: column;
align-items: center;
gap: 10px;
border-radius: 35px;
background: var(--Primary, #2091F9);
color :white;
border:none;
  cursor: pointer;
  color: var(--Light-text, #FFF);

/* Button */
font-family: Graphik;
font-size: 20px;
font-style: normal;
font-weight: 400;
line-height: 20px; /* 100% */
letter-spacing: 0.2px;
}

.contact-form button:hover {
  background-color: #0056b3;
}

.contact-info {
  width: 55%;
  display: flex;
  align-items: center;
  flex-direction: column;
  
}
.contact-items{
    width: 100%;
    display: flex;
align-items: flex-start;
gap: 52px;
}
.cotact-info-item{
display: flex;
flex-direction: column;
align-items: center;
gap: 10px;

}
.contact-info h5 {
    display: flex;
padding: 10px;
align-items: center;
gap: 10px;
color: var(--second-text, #374754);
text-align: center;
font-family: Graphik;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 23px; 
letter-spacing: 0.1px;
}


.map {
margin: 20px 0px;
}

.social-icons {
    width: 100%;
  display: flex;
  justify-content: flex-start;
  gap: 10px;
}


</style>
