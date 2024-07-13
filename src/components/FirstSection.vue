<template>
  <div class="firstSection">
    <div class="first-content">
      <h1>
        The best products <br />
        start with Figma
      </h1>
      <p>
        Most calendars are designed for teams. Slate is designed <br />for
        freelancers
      </p>
      <button>Try For Free</button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.firstSection {
  background: url(../assets/start-photo.png) rgb(255, 255, 255) 50% / cover
    no-repeat;
  margin: 0;
  color: white;
  display: flex;
  height: 100vh;
  /* width: 100vw; */
  /* padding-bottom: -150px; */
  /* padding: 80px 0px; */
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.first-content {
  display: flex;
  padding: 50px 0px;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 30px;
}
.first-content h1 {
  color: var(--Light-text, #fff);
  text-align: center;

  font-family: Graphik;
  font-size: 74px;
  font-style: normal;
  font-weight: 700;
  line-height: 84px;
  letter-spacing: 0.2px;
}
.first-content p {
  color: var(--Light-text, #fff);
  text-align: center;

  font-family: Graphik;
  font-size: 28px;
  font-style: normal;
  font-weight: 400;
  line-height: 40px;
  letter-spacing: 0.2px;
}
.first-content button {
  color: white;
  display: flex;
  width: 236px;
  padding: 16px 0px;
  flex-direction: column;
  align-items: center;
  border-radius: 35px;
  background: var(--Primary, #2091f9);
  outline: none;
  text-decoration: none;
  border: none;
  cursor: pointer;
}
</style>
