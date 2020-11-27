template>
  <div id="app">
    <img class="logo" alt="Vue logo" src="./assets/Logo.svg">
    <!-- Navigation Bar -->
<div class="navbar">
  <a class="link1" href="VueForm.vue">Our work v</a>
  <a class="link2" href="#">Design & Development</a>
  <a class="link3" href="#">Marking</a>
  <a class="link4" href="#">Get in touch -></a>
</div>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>


<!-- Header -->
<div class="header">
  <h4 class="subheading">We're Blend commerce</h4>
  <h1 class="heading"><b>Your Vision</b></h1>
  <h1 class="heading1">Our Insights</h1>
  <p>Experts in delivering solutions for <img src="./assets/shopfiy.svg" alt="Girl in a jacket" width="100" height="50">
  <br>
  <div class="stars">
<img src="./assets/Star.svg" alt="Girl in a jacket" width="10" height="10">
<img src="./assets/Star.svg" alt="Girl in a jacket" width="10" height="10">
<img src="./assets/Star.svg" alt="Girl in a jacket" width="10" height="10">
<img src="./assets/Star.svg" alt="Girl in a jacket" width="10" height="10">
<img src="./assets/Star.svg" alt="Girl in a jacket" width="10" height="10">
5 of 5 on <img src="./assets/experts.svg" alt="Girl in a jacket" width="100" height="50">

</div>
</div>

<!-- Navigation Bar -->

<div class="container">
  <div class="white-box">
<img src="./assets/sandbox.svg" alt="Girl in a jacket" width="100" height="50">
<img src="./assets/smsbump.svg" alt="Girl in a jacket" width="100" height="50">
<img src="./assets/Archetype.svg" alt="Girl in a jacket" width="100" height="50">
<img src="./assets/Klaviyo.svg" alt="Girl in a jacket" width="100" height="50">
<img src="./assets/reviews.svg" alt="Girl in a jacket" width="100" height="50">
<img src="./assets/pushowl.svg" alt="Girl in a jacket" width="100" height="50">
<img src="./assets/lion.svg" alt="Girl in a jacket" width="100" height="50">


    <div class="featured">

    </div>

  
  </div>
</div>


</body>
  </div>
  
</template>

<script>


export default {
  name: 'App',
  components: {

  }
}
</script>

<style>

.header {
padding-left: 170px;
    text-align: left;
    color: white;
        padding-top: 16px;
}

#app {
    padding-right: 900px;
  padding-top: 60px;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background-image: url("./assets/Shapes.svg");
  height: 1000px;
}

.class { 
  padding-top: 10px;
}
.subheading {
color: forestgreen;
    font-style: italic;
    font-size: 29px;
    /* width: 1000px; */
}
.heading {
color: white;
    font-size: 100px;
    width: 1000px;
    top: 172px;
    font-weight: bold;
    position: absolute;
}
.heading1 {
color: white;
    font-size: 100px;
    width: 1000px;
    font-weight: 100;
  background-image: url("./assets/smaller.png");
}
.navbar {
      display: flex;

}
.link1 {
    color: white;
  text-decoration: none;
      position: absolute;
    left: 794px;
  bottom: 550px;
}
.link2 {
    color: white;
  text-decoration: none;
      position: absolute;
    left: 896px;
    bottom: 550px;
}
.link3 {
    color: white;
  text-decoration: none;
    position: absolute;
    left: 1090px;
    bottom: 550px; }
.link4 {
    color: white;
  text-decoration: none;
      position: absolute;
    left: 1180px;
    bottom: 550px;
}
.link4:focus {
      text-decoration: underline;
    text-decoration-color: forestgreen;
    text-decoration: 10px solid;
    
}
.container {position: absolute; margin: 0; width:%; min-height: 600px;margin-left: 115px;
    padding-top: 203px;
}
.white-box {
    position: absolute;
    width: 800px;
    height: 60px;
    margin-top: 50px;
    margin-left: auto;
    margin-right: auto;
    position: absolute;
    padding: 30px;
    box-shadow: 0 1px 2px rgba(0,0,0,0.15);
    border-radius: 5px;
    padding-left: 30px;
    padding-right: 30px;
    background-color: white;
}
 img {
   padding-left: 10px;
 }
 p {
   width: 600px;
   
 }

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .navbar {   
    flex-direction: column;
  }
  .subheading {
    color: forestgreen;
    font-style: italic;
    font-size: 29px;
    width: 1000px;
        position: absolute;
    left: 15px;

}
.heading {
  position: absolute;
  left: 22px;
}
.heading1 {
  position: absolute;
      left: 9px;
    top: 300px;

}
}
</style>
