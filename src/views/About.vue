<template>
  <div class="about " style=" background-color:black;">
    
     <div class="card  text-white" style="background-color:black; letter-spacing:4px; height:800px;">
  <img src="../assets/b.jpg" class="card-img" alt="..." style="height:600px; width:100%">
  <div class="card-img-overlay" style="padding-top:500px; ">
    <h5 class="card-title h1">APPLE EVENT</h5>
    <p class="card-text" style=" text-transform: uppercase; padding-top:10px">please join us for an APPLE special event at </p> <p>THE STEVE JOBS THEATER</p>
    <p class="card-text">AND</p>
    <p class="card-text"> WATCH IT LIVE ONLY ON APPLE VIDEOS</p>
    </div>
    </div>
    
   <div class="card wrapper"  >
  <div class="card-body" style="">
    <div class="container">

<div class="row g-5 gt-3 pt-3" style="margin-left:100px">
  <div class="col-6 col-sm-4" >
     <div class="flip-card" >
  <div class="flip-card-inner" style="border-radius:30px;">
    <div class="flip-card-front">
      <img src="../assets/i.jpg" alt="Avatar ">
    </div>
    <div class="flip-card-back pt-5" >
      <h1>IPHONE 16</h1>
      <p>Architect & Engineer</p>
      <p>We love that guy</p>
    </div>
  </div>
</div>

  </div>
  <div class="col-6 col-sm-4" >
    <div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      <img src="../assets/w.jpg" alt="Avatar" >
    </div>
    <div class="flip-card-back">
      <h1>John Doe</h1>
      <p>Architect & Engineer</p>
      <p>We love that guy</p>
    </div>
  </div>
</div>
  </div>
  <div class="col-6 col-sm-4">
        <div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      <img src="../assets/p.jpg" alt="Avatar" >
    </div>
    <div class="flip-card-back">
      <h1>John Doe</h1>
      <p>Architect & Engineer</p>
      <p>We love that guy</p>
    </div>
  </div>
</div>
    
    
  </div>
  <div class="col- col-sm-4" >
        <div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      <img src="../assets/t.jpg" alt="Avatar" >
    </div>
    <div class="flip-card-back">
      <h1>John Doe</h1>
      <p>Architect & Engineer</p>
      <p>We love that guy</p>
    </div>
  </div>
</div>
  </div>
   <div class="col- col-sm-4" >
        <div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      <img src="../assets/h.jpg" alt="Avatar" >
    </div>
    <div class="flip-card-back">
      <h1>John Doe</h1>
      <p>Architect & Engineer</p>
      <p>We love that guy</p>
    </div>
  </div>
</div>
  </div>
  <div class="col-6 col-sm-4">
        <div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      <img src="../assets/tv.jpg" alt="Avatar" >
    </div>
    <div class="flip-card-back">
      <h1>John Doe</h1>
      <p>Architect & Engineer</p>
      <p>We love that guy</p>
    </div>
  </div>
</div>
  </div>
</div>
    </div>
</div>
   </div>
    
  </div>
</template>
<style scoped>
.wrapper {
  position: relative;
  width: auto;
  height: auto;
  color: #FFFFFF;
  
  background: linear-gradient(#80FFDB, #5390D9);;
}
.flip-card {
  background-color: transparent;
  width: 250px;
  height: 300px;
  
  
  perspective: 1000px; /* Remove this if you don't want the 3D effect */
}

/* This container is needed to position the front and back side */
.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}

/* Do an horizontal flip when you move the mouse over the flip box container */
.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

/* Position the front and back side */
.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden; /* Safari */
  backface-visibility: hidden;
}

/* Style the front side (fallback if image is missing) */
.flip-card-front {
  background-color: #bbb;
  color: black;
}

/* Style the back side */
.flip-card-back {
  background-color: gray;
  color: white;
  transform: rotateY(180deg);
}
img{
  height: 300px;
  width: 250px;
}

</style>
