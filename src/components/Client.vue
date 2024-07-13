<template>
<div class="client-item">
  <slot></slot>
</div>

</template>

<script>

export default {

}
</script>

<style>
.client-item{

 display: flex;
padding: 31px 40px;
flex-direction: column;
align-items: center;
gap: 15px;
border: 1px solid #D8D8D8;
background: var(--light-background, #FFF);
}
.client-item p{
color: var(--second-text, #374754);

/* H5 */
font-family: Graphik;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 23px; /* 143.75% */
letter-spacing: 0.1px;
}
.client-item img{

height: 63px;
}
</style>