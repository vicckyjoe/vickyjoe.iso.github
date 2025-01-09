<!DOCTYPE html>
<style>
  header{
    background-color: #333;
    color:#fff;
    padding: 10px 0;
    text-align: center
  }
  body{
    font-family:Arial, sans-serif;
    line-height: 1.6;
  }
  {
    margin:0;
    padding:0;
    box-sizing: border-box;
  }
header h1{
    margin0;
  }
  nav ul{
    list-style:none;
    display: flex;
    justify-content: center;
    padding: 0;

  }
  nav ul li{
    margin: 020px;

  }
  nav ul li a{
    color:#fff;
    text-decoration: none;

  }
  section{
    padding:20px;
    margin: 20px;
    max-width: 1000px;
    margin-left: auto;
    margin-right: auto;

  }
  #about, #projects, #contact{
    background-color: #f4f4f4;
    padding: 20px;
    border-radius: 10px;
  }
.project{
  margin: 15px0;
}
footer{
  background-color:#333;
  color:#fff;
  text-align: center;
  padding: 10px 0;


}
button{
  background-color:#333
  color: white;
  border: none;
  padding: 10px;
  cursor: pointer;
}
button.hover{
  background-color: #555;

}
form{
  display: flex;
  flex-direction: column;
}
form label {
  margin: 10px 0 5px;

}
form input, form textarea{
padding: 10px;
margin-buttom: 10px;
border: 1px solid #ccc;
border-radius: 5px;
}
</style>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport"
    content="width=device-width, 
    initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" 
    herf="style.css">
  </head>
  <body>
    <!--Header and Navigation-->
    <header>
      <h1>My  Portfolio</h1>
      <nav>
        <ul>
          <li>
            <a herf="#about">About Me</a>
          </li>
          <li> <a herf="#projects">Projects</a></li>
          <li> <a herf="#contact">Contact</a></li>

    </ul>
  
      </nav>
    </header>
    <!--About Me Section-->
    <section id="about">
      <h2>About Me</h2>
      <p>
        Hello! i'm VICTOR IFEANYI a passionate web developer 
        with experience in creating dynamic and 
        responsive websites. I love coding and am
        constantly learning new technologies to
        enhance my skills.
      </p>
    </section>
    <!--Projects Section-->
    <section id="projects">
      <h2>Projects</h2>
      <div class="projects">
        <h3>Projects 1</h3>
        <p>Eco-Friendly Smart Garden:
        A self-watering, solar-powered garden system using sensors
        and AI to optimize plant growth, reducw waste,
        and promote sustainablity.
        </p>
      </div>
      <div class="projects">
        <h3>Project 2</h3>
        <p>Smart Learning Companion:
          A mobile app that uses AI to create 
          personalized learning plans for students,
          offering real-time feedback, interactive lessons,
          and adaptive assessments to improve academic 
          performance and engagement.
        </p>
      </div>
      <div class="project">
        <h3>project 3</h3>
        <p>CropGuard; 
          A drone-based monitoring system that
          uses AI-powered cameras to detect crop 
          diseases, pests, and nutrient deficiencues, 
          providing farmers with real-time insights 
          to optimize yields and reduce waste
          
        </p>
      </div>
    </section>
    <!--Contact Form Section-->
    <section id="contact">
      <h2>
        Contact Me
      </h2>
      <form id="comtactForm">
        <label for="name">
          Name:
        </label>
        <input type="text" id="name"
        name="name" required>
        <label for="email">Email:</label>
        <input type="email" id="email"  
        name="email"required>
        <label for="message">Message:</label>
        <textarea id="message" name="message"
        required></textarea>
        <button type="submit">Send</button>
      </form>
    </section>
    <!--Footer-->
    <footer>
      <p>&copy; 2024 My Portfolio</p>
    </footer>
    <script src="script.js"></script>
  
  </body>
  </html>
  
