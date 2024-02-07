# HCI_Midterm
combined HTML and CSS


/HTML/
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Personal Portfolio Website</title>
    <!----CSS link----->
    <link rel="stylesheet" href="styleport.css" />
  </head>
  <body>
    <div class="hero">
      <nav>
        <img src="logoport.jpg" class="logo" />
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Service</a></li>
          <li><a href="#">Portfolio</a></li>
          <li><a href="#">Blog</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
        <a href="#" class="btn">Resume</a>
      </nav>

      <div class="content">
        <span class="title">Freelance Web Developer</span>
        <h1>Hello, I’m <span>Aquixa</span></h1>
        <p>
          I'm Aquixa Sab, a passionate freelance web developer with over 5 years of experience in crafting visually stunning and functional websites for clients worldwide.
        </p>


        <section id="about">
    <div class="container">
      <h2>Projects:</h2>
      <p>

         <p>Client: ABC Company
        <br> Description: Developed a responsive e-commerce website for ABC Company using HTML5, CSS3, JavaScript, and WooCommerce.
         

         <p>Client: XYZ Restaurant
         <br>Description: Designed and implemented a modern, mobile-friendly website for XYZ Restaurant using WordPress and Elementor.
         

         <p>Client: DEF Nonprofit
         Description: Collaborated with DEF Nonprofit to create a custom donation platform using PHP and MySQL, integrated with Stripe for payment processing.
         </p>
    </div>




        </section>
  <section id="Service Offered">
    <div class="container">
      <h2>Services Offered:</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <p class="card-text">
                 <p>Website Design
                    <br>Front-end Development
                    <br>Back-end Development
                    <br>E-commerce Solutions
                    <br>CMS Customization
                    <br>Responsive Web Design</p>
        </div>





        </section>
  <section id="Skills:">
    <div class="container">
      <h2>Skills:</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <p class="card-text">
                 <p>  HTML5
                      <br>CSS3/SASS
                      <br>JavaScript/ES6
                      <br>PHP
                      <br>WordPress
                      <br>WooCommerce
                      <br>Bootstrap
                      <br>jQuery
                      <br>MySQL
                      <br>Git</p>
                      </p>
                      </p>
              
        </div>


        </section>
  <section id="Skills:">
    <div class="container">
      <h2>Testimonials:</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <p class="card-text">
                 <p>  "Beane delivered an outstanding website for our business. His attention to detail and commitment to excellence are truly commendable." - ABC Company
                      <p>"Working with Beane was a pleasure. He understood our requirements perfectly and delivered a website that exceeded our expectations." - XYZ Restaurant
                      </p>





        





        <a href="#" class="btn">Contact Me</a>
      </div>
    </div>
  </body>
</html>





/CSS/
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}
a {
  text-decoration: none;
}
.hero {
  width: 100%;
  height: 100vh;
  background: url(img/bg.png);
  background-size: cover;
}
nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 30px 100px;
}
.logo {
  max-height: 60px;
}
nav ul li {
  list-style: none;
  display: inline-block;
  padding: 10px 20px;
}
nav ul li a {
  color: #1d1d24;
  position: relative;
  padding: 5px 0;
}
nav ul li a:hover {
  color: #fd4766;
}
nav ul li a:after {
  content: "";
  position: absolute;
  left: 0;
  width: 0;
  height: 3px;
  background: #fd4766;
  transition: 0.3s;
  bottom: 0;
}
nav ul li a:hover:after {
  width: 100%;
}
.btn {
  color: #fff;
  font-size: 16px;
  text-transform: uppercase;
  letter-spacing: 2px;
  padding: 16px 40px;
  border-radius: 500px;
  display: inline-block;
  font-weight: 500;
  transition: all 0.4s ease-in-out;
  background-size: 152% 100%;
  background: #fd4766;
  border: 2px solid #fd4766;
}
.btn:hover {
  background: transparent;
  border-color: #fd4766;
  color: #fd4766;
}
.content {
  position: absolute;
  top: 35%;
  left: 8%;
}
.content .title {
  color: #0a0a0a;
  font-size: 15px;
  text-transform: uppercase;
  letter-spacing: 4px;
  display: inline-block;
  margin-bottom: 20px;
  background: linear-gradient(
    120deg,
    #1c99fe 20.69%,
    #7644ff 50.19%,
    #fd4766 79.69%
  );
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.content h1 {
  color: #1f1f25;
  font-size: 75px;
  font-weight: 900;
  line-height: 90px;
  text-transform: inherit;
  width: 70%;
}
.content h1 span {
  color: #fd4766;
}
.content p {
  width: 55%;
  color: #202020;
  margin-top: 25px;
  margin-bottom: 30px;
}
