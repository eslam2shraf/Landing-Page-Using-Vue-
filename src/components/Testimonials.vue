<template>
  <div class="Testimonials">
  <div class="test-header">
      <h2>Testimonials</h2>
  </div>
<div class="ibm-part">
    <div class="ibm-logo">
        <img src="../assets/ibm.svg" alt="IBM-Logo">
    </div>
    <div class="ibm-content">
        <p>Most calendars are designed for teams. Slate is designed for freelancers <br/>
who want a simple way to plan their schedule.</p>
    </div>
    <div class="organizer">
        <img src="../assets/person.svg" alt="Designer">
        <div class="organizerDetails">
            <p>Organize across</p>
            <p>Ui designer</p>
        </div>
    </div>
</div>
<div class="more-Testimonials">
    <button>More Testimonials</button>
</div>

  </div>
</template>

<script>
export default {

}
</script>

<style>
.Testimonials{
    display: flex;
padding: 100px 0px;
flex-direction: column;
align-items: center;
gap: 80px;
align-self: stretch;
}
.test-header{
    display: flex;
padding: 10px;
align-items: center;
gap: 10px;
color: var(--text, #252B42);
text-align: center;

/* H2 */
color: var(--text, #252B42);
text-align: center;


}
.test-header h2{
    font-family: Graphik;
font-size: 48px;
font-style: normal;
font-weight: 400;
line-height: 55px; /* 114.583% */
letter-spacing: 0.2px;
}
.ibm-part{
    display: flex;
flex-direction: column;
align-items: center;
gap: 50px;
}
.ibm-part p{
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
.organizer{
    display: flex;
align-items: center;
gap: 13px;
}
.organizer p{
    color: var(--second-text, #374754);

/* H5 */
font-family: Graphik;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 23px; /* 143.75% */
letter-spacing: 0.1px;
}
.organizerDetails{
    display: flex;
flex-direction: column;
align-items: flex-start;
}
.more-Testimonials button{
    display: flex;
padding: 16px 47px;
flex-direction: column;
align-items: center;
border-radius: 35px;
background: var(--Primary, #2091F9);
color: var(--Light-text, #FFF);

/* H3 */
font-family: Graphik;
font-size: 20px;
font-style: normal;
font-weight: 700;
line-height: 28px; /* 140% */
letter-spacing: 0.1px;
border: none;
cursor: pointer;
}
</style>