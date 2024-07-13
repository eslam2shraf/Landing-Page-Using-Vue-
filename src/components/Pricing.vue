<template>
  <div class="pricing">
    <div class="pricing-header">
      <h2>Pricing</h2>
      <h4>Most calendars are designed for teams. <br/>
Slate is designed for freelancers</h4>
    </div>
    <div class="pricing-items">
         <div :class="['active-item', FreeisActive ? 'active' : 'notActive']" @mouseenter="ActiveFree">

         <div class="start-data">
             <h3>Free</h3>
             <h5>Organize across all<br/> 
apps by hand</h5>
         </div>
         <div class="price">
             <div class="number">0</div>
             <div class="sign">
                 <h3>$</h3>
                 <h4>Per Month</h4> 
             </div>
         </div>
         <div class="price-list">
             <ul>
               <li>Pricing Feature</li>
               <li>Pricing Feature</li>
               <li>Pricing Feature</li>
               <li>Pricing Feature</li>
               <li>Pricing Feature</li>
                 
             </ul>
         </div>
         <div class="order-button"><button> <span>Order Now</span></button>
            </div>
     </div>
     <div :class="['active-item', StandardIsActive ? 'active' : 'notActive']" @mouseenter="ActiveStandard">

         <div class="start-data">
             <h3>STANDARD</h3>
             <h5>Organize across all<br/> 
apps by hand</h5>
         </div>
         <div class="price">
             <div class="number">10</div>
             <div class="sign">
                 <h3>$</h3>
                 <h4>Per Month</h4> 
             </div>
         </div>
         <div class="price-list">
             <ul>
               <li>Pricing Feature</li>
               <li>Pricing Feature</li>
               <li>Pricing Feature</li>
               <li>Pricing Feature</li>
               <li>Pricing Feature</li>
                 
             </ul>
         </div>
         <div class="order-button"><button> <span>Order Now</span></button>
            </div>
     </div>
      <div :class="['active-item', BusinessIsActve ? 'active' : 'notActive']" @mouseenter="ActiveBusiness">
    <!-- <div class="active-item , notActive" @mouseenter="ActiveBusiness"> -->
         <div class="start-data">
             <h3>BUSINESS</h3>
             <h5>Organize across all<br/> 
apps by hand</h5>
         </div>
         <div class="price">
             <div class="number">99</div>
             <div class="sign">
                 <h3>$</h3>
                 <h4>Per Month</h4> 
             </div>
         </div>
         <div class="price-list">
             <ul>
               <li>Pricing Feature</li>
               <li>Pricing Feature</li>
               <li>Pricing Feature</li>
               <li>Pricing Feature</li>
               <li>Pricing Feature</li>
                 
             </ul>
         </div>
         <div class="order-button"><button> <span>Order Now</span></button>
            </div>
     </div>

    </div>


  </div>
</template>

<script>
export default {
    data(){
        return{
         FreeisActive:false,
         StandardIsActive:true,
         BusinessIsActve:false
        }
     
    },
    methods:{
       ActiveFree(){
           this.FreeisActive=true;
           this.StandardIsActive=false;
           this.BusinessIsActve=false
       },
             ActiveStandard(){
           this.FreeisActive=false;
           this.StandardIsActive=true;
           this.BusinessIsActve=false
       },
             ActiveBusiness(){
           this.FreeisActive=false;
           this.StandardIsActive=false;
           this.BusinessIsActve=true
       },
    }

};
</script>

<style>

.pricing-items{
    display: flex;
flex-direction:row;
align-items: center;
justify-content: center;
gap: 21px;

}
.pricing{
background: var(--Dark-background, #252B42);
    display: flex;
padding: 100px 0px;
flex-direction: column;
align-items: center;
gap: 80px;
align-self: stretch;

}
.pricing-header{
    display: flex;
flex-direction: column;
align-items: center;
gap: 7px;
}
.pricing-header h2 {
color: var(--Light-text, #FFF);
text-align: center;
display: flex;
padding: 10px;
align-items: center;
gap: 10px;
/* H2 */
font-family: Graphik;
font-size: 48px;
font-style: normal;
font-weight: 400;
line-height: 55px; /* 114.583% */
letter-spacing: 0.2px;
}
.pricing-header h4{
    display: flex;
padding: 10px;
align-items: center;
gap: 10px;
color: var(--Light-text, #FFF);
text-align: center;

/* H4 */
font-family: Graphik;
font-size: 28px;
font-style: normal;
font-weight: 400;
line-height: 40px; /* 142.857% */
letter-spacing: 0.2px;
}
.active-item{
    display: flex;
width: 335px;
padding: 40px 10px;
flex-direction: column;
align-items: center;
gap: 30px;
border-radius: 10px;
border: 1px solid #DEDEDE;
background: var(--Primary, #2091F9);
box-shadow: 0px 13px 19px 0px rgba(0, 0, 0, 0.07);
}
.start-data{
    display: flex;
flex-direction: column;
align-items: center;
}
.start-data h3{
    display: flex;
padding: 3px 0px;
align-items: center;
gap: 10px;
color: var(--Light-text, #FFF);

/* H3 */
font-family: Graphik;
font-size: 20px;
font-style: normal;
font-weight: 700;
line-height: 28px; /* 140% */
letter-spacing: 0.1px;
}
.start-data h5{
    display: flex;
align-items: center;
color: var(--Light-text, #FFF);
text-align: center;

/* H5 */
font-family: Graphik;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 23px; /* 143.75% */
letter-spacing: 0.1px;
}
.price{
    display: flex;
height: 61px;
align-items: flex-start;
}
.number{
    display: flex;
padding: 0px 10px;
align-items: center;
gap: 10px;
color: var(--Light-text, #FFF);

/* H1 */
font-family: Graphik;
font-size: 74px;
font-style: normal;
font-weight: 700;
line-height: 84px; /* 113.514% */
letter-spacing: 0.2px;
}
.sign{
    padding-top:15px ;
    display: flex;
flex-direction: column;
align-items: flex-start;
justify-content: center;
}
.sign h3{
    color: var(--Light-text, #FFF);

/* H3 */
font-family: Graphik;
font-size: 20px;
font-style: normal;
font-weight: 700;
line-height: 28px; /* 140% */
letter-spacing: 0.1px;
}
.sign h4{
    color: var(--Light-text, #FFF);

/* H5 */
font-family: Graphik;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 23px; /* 143.75% */
letter-spacing: 0.1px;
}
.price-list{
    display: flex;
flex-direction: column;
align-items: center;
align-self: stretch;

}
.price-list ul{
text-decoration: none;
list-style: none;
}
.price-list li{
    display: flex;
padding: 10px;
align-items: center;
gap: 10px;
color: var(--Light-text, #FFF);

/* Link */
font-family: Graphik;
font-size: 15px;
font-style: normal;
font-weight: 400;
line-height: 28px; /* 186.667% */
letter-spacing: 0.2px;
}
.order-button button{

display: flex;
padding: 18px 38px;
flex-direction: column;
align-items: center;
gap: 10px;
align-self: stretch;
border-radius: 35px;
background: var(--Light-text, #FFF);
border: none;
cursor: pointer;
}
.order-button span{
    color: var(--Primary, #2091F9);

/* Button */
font-family: Graphik;
font-size: 20px;
font-style: normal;
font-weight: 400;
line-height: 20px; /* 100% */
letter-spacing: 0.2px;

}
.notActive{
    width: 300px;
padding: 20px;
    border-radius: 10px;
border: 1px solid #DEDEDE;
background: var(--light-background, #FFF);
box-shadow: 0px 13px 19px 0px rgba(0, 0, 0, 0.07);
}   
.notActive li{
    color: var(--text, #252B42);
}
.notActive h3{
    color: var(--text, #252B42);
}
.notActive h4{
    color: var(--text, #252B42);
}
.notActive h5{
    color: var(--text, #252B42);
}
.notActive .number{
       color: var(--text, #252B42);
}
.notActive button{
    background: var(--Primary, #2091F9);
    cursor: pointer;
}
.notActive span{
   color: var(--Light-text, #FFF);
}
</style>
