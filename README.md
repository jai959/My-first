
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jai's Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
  body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #ff9966, #ff5e62);
      color: #fff;
      overflow-x: hidden;
    }
    header {
      text-align: center;
      padding: 50px 20px;
      background-color: rgba(0, 0, 0, 0.4);
      border-bottom: 2px solid #fff;
      position: relative;
    }
    header .profile-img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 5px solid #fff;
      position: absolute;
      top: 100%;
      left: 50%;
      transform: translate(-50%, -50%);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    header .profile-img:hover {
      transform: translate(-50%, -50%) scale(1.1);
      box-shadow: 0 0 20px #fff;
    }
    header h1 { font-size: 2.5rem; margin-top: 100px; }
    header h2 {
      margin: 10px 0;
      font-size: 1.5rem;
      font-weight: 300;
    }
    nav {
      margin-top: 40px;
    }
    nav a {
      text-decoration: none;
      color: #fff;
      margin: 0 15px;
      font-weight: 600;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #ffddc1;
    }
    section {
      padding: 50px 20px;
      text-align: center;
    }
    .card {
      background-color: rgba(255, 255, 255, 0.2);
      margin: 20px auto;
      padding: 20px;
      border-radius: 15px;
      max-width: 500px;
      transition: transform 0.3s ease;
    }
    .card:hover {
      transform: scale(1.05);
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: rgba(0, 0, 0, 0.4);
      border-top: 2px solid #fff;
    }
  </style>
</head>
<body>
  <header>
    <img src="image.jpg" alt="Profile Image" class="profile-img">
    <h1>Jai's Portfolio</h1>
    <h2>Web Developer & Problem Solver</h2>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <div class="card">
      <p>Hello! I’m Jai, a passionate learning
      who loves creating elegant web solutions. Based in Tamil Nadu, India.</p>
    </div>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="card">
      <p>Java-sql-c++-python- Problem-Solving basics</p>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="card">
      <p>Coming soon! Stay tuned for my exciting creations.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <div class="card">
      <p>Email: jjai98993@gmail.com</p>
      <p>Phone: +91 8940781782</p>
    </div>
  </section>
  <section id="resume">
  <h2>Resume</h2>
  <div style="perspective: 1000px;">
    <div style="width: 300px; height: 200px; margin: 0 auto; position: relative; transform-style: preserve-3d; transition: transform 0.6s;" 
         onmouseover="this.style.transform='rotateY(180deg)'" 
         onmouseout="this.style.transform='rotateY(0deg)'">
      <div style="position: absolute; width: 100%; height: 100%; backface-visibility: hidden; background: #ff5e62; color: #fff; display: flex; align-items: center; justify-content: center; border-radius: 10px;">
        <p>Click to flip!</p>
      </div>
      <div style="position: absolute; width: 100%; height: 100%; backface-visibility: hidden; background: #fff; color: #000; transform: rotateY(180deg); display: flex; align-items: center; justify-content: center; border-radius: 10px;">
        <a href="resume.png" target="_blank" style="text-decoration: none; color: #fff; background: #ff5e62; padding: 10px 20px; border-radius: 5px; font-weight: 600;">Download Resume</a>
      </div>
    </div>
  </div>

</section>
  <footer>
    <p>© 2025 Jai's Portfolio. All Rights Reserved.</p>
  </footer>

</body>
</html>
