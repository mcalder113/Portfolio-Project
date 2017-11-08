@import url('https://fonts.googleapis.com/css?family=Space+Mono');
nav a {
  font-family: "Space Mono";
  display: inline-block;
  padding: 10px 10px;
  text-decoration: none;
  color: black;
}
.home {
    font-family: "Space Mono";
    text-align: center;
    height:100vh;
    width:100%;      
    background:url(https://uproxx.files.wordpress.com/2016/07/point-break-quotes.jpg?quality=100&w=650)no-repeat 50% 50% ;
  }
.About{
  margin: 25px;
  font-family: "Space Mono";
  font-size: 15px;
}
.Projects {
    text-align: center;
    font-family: "Space Mono"; 
    font-size: 30px;
}    
.Contact {
    text-align: center;
    font-family: "Space Mono";  
    font-size: 35px;
}  
<header>
      <div class="wrapper">
          <nav align="right">
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#p">Projects</a>
            <a href="#f">Contact</a>
          </nav>
      </div>
   <body>
     <section class="home">
       <h1>Michael A. Calder<br/>Full Stack Developer</h1>
     </section>
     <section class="About">
       <h2 align="center">About Me</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
     </section>  
 <section>
       <h3 class="Projects">Projects</h3>
<div class="container">       
 <div class="row">
  <div class="col-md-4">
    <div class="thumbnail">
        <img src="https://i5.walmartimages.com/asr/8ad02e53-7a94-4e69-840d-d9ebd20adfbf_1.c262f79b6a96ef0979eb08e6a8c3ffb5.jpeg?odnHeight=450&odnWidth=450&odnBg=FFFFFF" alt="Lights" style="width:25%">
        <div class="caption">
          <p>Lorem ipsum...</p>
       </div>
    </div>
  </div>
  <div class="col-md-4">
    <div class="thumbnail">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/36/Hopetoun_falls.jpg" alt="Nature" style="width:25%">
        <div class="caption">
          <p>Lorem ipsum...</p>
       </div>
    </div>
  </div>
  <div class="col-md-4">
    <div class="thumbnail">
<img src="http://www.fjords.com/wp-content/uploads/photo-gallery/DSC_9011.jpg" alt="Fjords" style="width:25%">
    <div class="caption">
        <p>Lorem ipsum...</p>
      </div>
    </div>
</section> 
     <section class="Contact">
       <h4>Contact Me</h4>
     </section> 
