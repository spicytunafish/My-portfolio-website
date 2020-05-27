<html>

<head>
<style>
body {background-color: powderblue;}
<section id="welcome-section">
<h1>Samuel "spicytuna" Carl Kleinitz Schultz<h1/>
</section>
 
<section id="about section">
<h1>My birthname is Samuel, but I have endless aliases. Stick to your routines, trust the process. Live to see another day.</h1>
</section>

<section id="navbar">
  <div class="navbar">
    <a href="#welcome-section">Home</a>
     <a href="https://www.youtube.com/channel/UC2io3JoHd2OyCGPwoMjt_Wg?view_as=subscriber" target="_blank">Youtube</a>
<a href="https://twitch.tv/spicytunatv" target="_blank">Twitch</a>
<a href="https://instagram.com/samuelckschultz" target="_blank">Instagram</a>
<a href="#projects">Projects</a>
</div>

<section id="projects">
<div class="project-tile">
<h2>Coding and previous experience</h2>
<p>I have experience using several coding languages, and have worked with different tasks related to webdesign. I have incorporated my own panels into my Twitch channel, and I'm currently working on my graphic design skills.</p>
</div>
    
<div class="project-tile">
<h2>Education and work</h2>
<p>Majority of my youth education took place in Denmark, where I lived before moving to Norway. When I applied to start at Kuben VGS, I initially wanted to become an electrician, but my passion and interest for computers and how to incorporate them into your daily life made me change my opinion. Now I have one year left to go untill I can apply for university, where I want to study game development or computer engineering.</p>
</div>

<div class="project-tile">
<h2>Ruby on Rails</h2>
<p>I have used Heroku to make my own app as a website. It's very straight forward and intuitive, and your are more than welcome to check out the <a href="https://pure-journey-13452.herokuapp.com/cars" target="_blank">app here.</a>
</section>
<sectin id="profile-link">
        <div class="right">
          <a href="https://github.com/spicytunafish"target="_blank"><button>GitHub profile</button> </a>
  </section>
  
  
body {
  background-color: green;
  color: white;
}

#welcome-section {
  background-color: violet;
  font-size: 40px;
  color: black;
  padding: 40px;
  text-align: center;
  height: 100vh;
  
}

.project-tile {
  background-color: white;
  color: black;
  margin: 20px;
  padding: 20px;
}

.navbar {
  overflow: hidden;
  background-color: #333;
  position: fixed;
  top: 0;
  width: 35%;
}

.navbar a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.navbar a:hover {
  background: #ddd;
  color: black;
}
.btn {
  display: inline-block;
  background: #f0f8ff;
  border: 0;
  line-height: 2.5em;
  padding: 0 0 0 1em;
  margin-bottom: 1em;
  outline: none;
  text-decoration: none;
  color: #dc143c;
}

  .arrow {
    display: inline-block;
    line-height: 2.5em;
    text-align: center;
    background: #696969;
    color: red;
    font-size: 1em;
    width: 2.5em;
    transition: margin 200ms;
    margin-left: .75em;
  }
}
@media only screen and (max-width: 1300px) {
  body {
    background-color: lightblue;
  }
}

h1   {color: blue;}
p    {color: red;}
</style>
</head>

<body>
<h1>A Web Page</h1>
<p id="demo">A Paragraph</p>
<button type="button" onclick="myFunction()">Try it</button>

<script>
function myFunction() {
 document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>

</body>
</html>
