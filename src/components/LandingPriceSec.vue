<template>
<h1 class="section-title">Our Best Sellers</h1>
<div class="row">
  <div class="column">
<div class="card" onclick="this.classList.toggle('expanded')"><br>
<img src="https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fgadgetsmagazine.com.ph%2Fwp-content%2Fuploads%2F2015%2F05%2FToyota-Wigo_DSCF9803.jpg&f=1&nofb=1" height="200" class="card_img">
  <div class="text1">
    <div class="text-content">
      <h1 class="title">Toyota Wigo</h1>
      <div class="body-text">
        Car Year: 2018 <br>
        Engine type: Gas <br>
        Mileage: 60,000 km <br>  
        </div><br><br>
    <a href="#" class="btn btn-primary">Rent Now</a>
    </div>
  </div>
  <svg class="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 35" width="30"><path d="M5 30L50 5l45 25" fill="none" stroke="#000" stroke-width="5"/></svg>
</div>
  </div>

  <div class="column">
<div class="card" onclick="this.classList.toggle('expanded')"><br>
<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2F2.bp.blogspot.com%2F-w4IOJ_HpMV4%2FXD1qT88Pe3I%2FAAAAAAAA49I%2FLAy1zQxUVsoVBYusEC4jydy207TGM-tDwCLcBGAs%2Fw1200%2F2019_toyota_vios_13xe.jpg&f=1&nofb=1" height="200" class="card_img">
  <div class="text1">
    <div class="text-content">
      <h1 class="title">Toyota Vios</h1>
      <div class="body-text">
        Car Year: 2017 <br>
        Engine type: Gas <br>
        Mileage: 88,000 km <br>  
        </div><br><br>
    <a href="#" class="btn btn-primary">Rent Now</a>
    </div>
  </div>
  <svg class="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 35" width="30"><path d="M5 30L50 5l45 25" fill="none" stroke="#000" stroke-width="5"/></svg>
</div>
  </div>
  
  <div class="column">
<div class="card" onclick="this.classList.toggle('expanded')"><br>
<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.pickuptruck2021.com%2Fwp-content%2Fuploads%2F2020%2F09%2F2021-Isuzu-D-Max-Exterior.jpg&f=1&nofb=1" height="200" class="card_img">
  <div class="text1">
    <div class="text-content">
      <h1 class="title">Isuzu D-Max</h1>
      <div class="body-text">
        Car Year: 2020 <br>
        Engine type: Diesel <br>
        Mileage: 22,000 km <br>  
        </div><br><br>
    <a href="#" class="btn btn-primary">Rent Now</a>
    </div>
  </div>
  <svg class="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 35" width="30"><path d="M5 30L50 5l45 25" fill="none" stroke="#000" stroke-width="5"/></svg>
</div>
  </div>
</div>
</template>


>>>>>>> Stashed changes
<style scoped>
#pricing-section{
    min-height: 40vh;
}
.section-title{
    text-align: center;
      font-family: 'Alegreya Sans', sans-serif;
  font-weight: 900;
}

/* Float four columns side by side */
.column {
  float: left;
  width: 33%;
  padding: 0 50px;
  padding-top: 10px;
}
/* Remove extra left and right margins, due to padding */
.row {
    margin: 0 -5px;
    display: block;
    align-content: center;
}
/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive columns */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
}

/* Style the counter cards */
@import url('https://fonts.googleapis.com/css?family=Alegreya+Sans:900');
.card {
  background: white;
  border-radius: 8px;
  box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
  cursor: pointer;
  height: 300px;
  margin: 20px;
  padding: 0 20px;
  position: relative;
  -webkit-tap-highlight-color: rgba(0,0,0,0.025);
  text-align: center;
  transition: height 1000ms;
  width: 320px;
}
@media (max-width: 767px) {
  .card {
    left: calc(50% - 20px);
    transform: translateX(-50%);
  }
}
.card.expanded {
  height: 450px;
}
.card_img{
    width: 100%;
    display: block;
}
.card.expanded  {
  transform: translateY(0);
}
.text1 {
  clip-path: polygon(0% 100%, 0 -90%, 50% -5%, 100% -90%, 100% 100%);
  -webkit-clip-path: polygon(0% 100%, 0 -90%, 50% -5%, 100% -90%, 100% 100%);
  transition: clip-path 1000ms;
}
.card.expanded .text1 {
  clip-path: polygon(0% 100%, 0 -100%, 50% -15%, 100% -100%, 100% 100%);
  -webkit-clip-path: polygon(0% 100%, 0 -100%, 50% -15%, 100% -100%, 100% 100%);
}

.text-content {
  transform: translateY(-320px);
  transition: transform 1000ms;
}
.card.expanded .text-content {
  transform: translateY(-15px);
}
.chevron {
  position: absolute;
  bottom: 20px;
  left: calc(50% - 15px);
  transform-origin: 50%;
  transform: rotate(180deg);
  transition: transform 1000ms;
}
.card.expanded .chevron {
  transform: rotate(0deg);
}
.title {
  font-family: 'Alegreya Sans', sans-serif;
  font-weight: 900;
  margin: 20px 0 12px;
}
</style>