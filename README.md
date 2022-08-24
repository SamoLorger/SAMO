<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
  <meta charset="utf-8">
  <title>Samo Lorger</title>
  <link rel="stylesheet" href="css/styles.css">
  <link rel="icon" href="favicon.ico">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Merriweather&family=Montserrat&family=Sacramento&display=swap" rel="stylesheet">
  <!--vrste pisave  -->
</head>

<body>
  <div class="top-container">
    <img class="top-cloud" src="images/cloud.png" alt="clodu-img">
    <h1>I'm Samo</h1>
    <h2>I am an IOS and Web Developer.</h2>
    <img class="bottom-cloud" src="images/cloud.png" alt="cloud-img">
    <img class="top-cloud" src="images/cloud.png" alt="clodu-img">
    <img src="images/mountain.png" alt="mountain-img">
  </div>
  <div class="middle-container">
    <div class="profile">
      <p></p>
      <img src="images/Samo Lorger125.jpg" alt="Samo Lorger125"class="Samo"/>
      <h2>Hello.</h2>
      <p>I'm a Developer and I make awesome things for awesome people</p>
      <p>I love helping people level up with creative coding on the web platform</p>
      <p>But also my ability to deliver innovative solutions to complex problems</p>
    </div>
    <hr>
    <div class="skills">
      <div class="skill-row">
        <img class="lorger222" src="images/lorger222.png" alt="lorger222.png">
      <h3>My Skills</h3>
        <p>I love to learn and have fun while doing it. What makes that even more awesome, is sharing it with you! </p>
        <p>C++ , C ,JvaScript</p>
      </div>
      <div class="skill-row">

        <img class="chess" src="images\chess.png" alt="chess.png">
        <h3>My Hobbies</h3 >
        <p>I like to go to the mountains i play chess and like any real guy i play video games. </p>

      </div>
    </div>
    <hr>
    <div class="contact-me">
      <h3>Get In Touch</h3>

    <p>Although I’m currently looking for a new opportunities, my inbox is always open.Whether you have a question or just want to say hi, I’ll try my best to get back to you</p>
    </div>
  </div>

  <div class="contact-me">

    <a class="btn" href="mailto:lorgersamo@gmail.com">CONTACT ME</a>
  </div>
  </div>


  <div class="bottom-container">
    <a class="footer-link" href="https://www.linkedin.com/in/samo-lorger-03a393139/">LinkedIn</a>
    <a class="footer-link" href="https://twitter.com/SamoLorger">Twitter</a>
    <a class="footer-link" href="https://www.appbrewery.co/">Website</a>
    <p class="copyright"> © Samo Lorger</p>
  </div>


</html>



body{
  margin: 0;
  text-align: center;
  font-family:"Merriweather", serif;
  font-size: 130%;
}
h1{
  font-size: 5.625rem;
  line-height: 2;
  margin: 100px auto 100 auto ;
  font-family: 'Sacramento', cursive;
  color: #66BFBF;
}

h2{
  font-family: 'Montserrat', sans-serif;
  font-size: 2.5rem;
  color: #66BFBF;
}

h3{
  font-family: 'Montserrat' , sans-serif;
  color: #66BFBF;
}

p{
  line-height: 2;
}
hr{
  border: dotted #CEE5D0 5px;
  border-bottom: none;
  width: 4%;
  margin: 100px auto;
  }

a{
color: #11999E;
font-family:"Merriweather", serif;
margin:10px 20px;
text-decoration: 0;
}
a:hover{
  color: #EAF6F6;
}


img{
border-radius:8%
}


.top-container {
background-color:#B9FFF8;
position: relative;
padding-top: 100px
}

.middle-container{
margin: 100px 0;

}

.bottom-container{
  background-color: #66BFBF;
  padding: 50px 0 20px;
}

.pro{
text-decoration: underline;
}
.contact-massage{
  width: 40%;
  margin: 40px;
}

.profile{
  width: 30%;
  margin: auto;
}
.top-cloud{
position: absolute;
right: 300px;
margin: 40px auto 60px;
}

.bottom-cloud{
position: absolute;
left:250px;
bottom: 300px;
}

.Samo {
  width: 40%;
  border-radius:50%;
}

.skill-row {
width: 50%;
margin:100px auto 100px auto;
text-align: left;
}


.lorger222{
  width: 20%;
  float: left;
  margin-right: 30px;
}


.chess{
  width: 20%;
  float: left;
  margin-right: 30px;
}

.contact-me{
  width: 40%;
  margin:40px auto 60px;
}

.copyright{
  color:#EAF6F6;
  font-size:0.75rem;
  padding: 20px 0;
}

.btn {
   background: #11CCD4;
   background-image: -webkit-linear-gradient(top, #11CCD4, #11999E);
   background-image: -moz-linear-gradient(top, #11CCD4, #11999E);
   background-image: -ms-linear-gradient(top, #11CCD4, #11999E);
   background-image: -o-linear-gradient(top, #11CCD4, #11999E);
   background-image: -webkit-gradient(to bottom, #11CCD4, #11999E);
   -webkit-border-radius: 8px;
   -moz-border-radius: 8px;
   border-radius: 8px;
   color: #FFFFFF;
   font-family: arial;
   font-size: 20px;
   font-weight: 100;
   padding:10px 20px 10px 20px;
   -webkit-box-shadow: 1px 1px 20px 0 #000000;
   -moz-box-shadow: 1px 1px 20px 0 #000000;
   box-shadow: 1px 1px 20px 0 #FFFFFF;
   text-shadow: 1px 1px 20px #000000;
   border: solid #337FED 1px;
   text-decoration: none;
   display: inline-block;
   cursor: pointer;
   text-align: center;
}

.btn:hover {
   border: solid #337FED 1px;
   background: #30E3CB;
   background-image: -webkit-linear-gradient(top, #30E3CB, #2BC4DC);
   background-image: -moz-linear-gradient(top, #30E3CB, #2BC4DC);
   background-image: -ms-linear-gradient(top, #30E3CB, #2BC4DC);
   background-image: -o-linear-gradient(top, #30E3CB, #2BC4DC);
   background-image: -webkit-gradient(to bottom, #30E3CB, #2BC4DC);
   -webkit-border-radius: 20px;
   -moz-border-radius: 20px;
   border-radius: 20px;
   text-decoration: none;
}
Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
