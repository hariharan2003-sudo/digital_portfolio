<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hariharan - Portfolio</title>
  <style>
    /* Basic styling - you can customize this further */
    body {
      font-family: 'Arial', sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
      color: #333;
      background-color: #f5f5f5;
    }
    
    header {
      background: linear-gradient(135deg, #6e8efb, #a777e3);
      color: white;
      text-align: center;
      padding: 2rem 0;
      position: relative;
      overflow: hidden;
    }
    
    .profile-photo {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 5px solid white;
      margin-bottom: 1rem;
    }
    
    .container {
      width: 80%;
      margin: 0 auto;
      padding: 2rem 0;
    }
    
    section {
      padding: 2rem 0;
    }
    
    #projects {
      background-color: #fff;
    }
    
    .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 1.5rem;
      margin-top: 1.5rem;
    }
    
    .project-card {
      background: white;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 1.5rem;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    
    form input, form textarea {
      width: 100%;
      padding: 0.8rem;
      margin-bottom: 1rem;
      border: 1px solid #ddd;
      border-radius: 4px;
    }
    
    button {
      background: #6e8efb;
      color: white;
      border: none;
      padding: 0.8rem 1.5rem;
      border-radius: 4px;
      cursor: pointer;
      font-size: 1rem;
    }
    
    button:hover {
      background: #5a7df4;
    }
    
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 1.5rem 0;
    }
    
    .cloud {
      position: absolute;
      background: white;
      opacity: 0.2;
      border-radius: 50%;
    }
    
    .cloud:nth-child(1) {
      width: 100px;
      height: 60px;
      top: 20%;
      left: 10%;
      animation: float 15s infinite linear;
    }
    
    .cloud:nth-child(2) {
      width: 150px;
      height: 90px;
      top: 40%;
      right: 15%;
      animation: float 20s infinite linear reverse;
    }
    
    @keyframes float {
      0% { transform: translateX(0) translateY(0); }
      50% { transform: translateX(50px) translateY(-20px); }
      100% { transform: translateX(0) translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <!-- Add your photo here when you have one -->
    <img src="hariharan.jpeg" alt="Hariharan" class="profile-photo">
    <h1>Hariharan</h1>
    <p>BCA Student | Web Developer</p>
    <div class="cloud"></div>
    <div class="cloud" style="top: 40%; animation-delay: 2s;"></div>
  </header>

  <!-- About Section -->
  <section id="about">
    <div class="container">
      <h2>About Me</h2>
      <p>Hello! I'm Hariharan, a passionate BCA student currently pursuing my Bachelor's in Computer Applications. I have strong skills in HTML, CSS, and JavaScript, and I'm enthusiastic about creating beautiful, functional websites. My goal is to become a full-stack developer and contribute to innovative web projects.</p>
    </div>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <div class="container">
      <h2>Skills</h2>
      <ul>
        <li>HTML5 & CSS3</li>
        <li>JavaScript (ES6+)</li>
        <li>Responsive Web Design</li>
        <li>Bootstrap Framework</li>
        <li>Basic Python Programming</li>
        <li>Database Management (SQL)</li>
      </ul>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <div class="container">
      <h2>Projects</h2>
      <div class="project-grid">
        <div class="project-card">
          <h3>College Management System</h3>
          <p>Developed a web-based college management system using HTML, CSS, and JavaScript to manage student records and attendance.</p>
        </div>
        <div class="project-card">
          <h3>E-commerce Product Page</h3>
          <p>Created a responsive product page for an e-commerce website with interactive features like image gallery and cart functionality.</p>
        </div>
        <div class="project-card">
          <h3>Personal Blog Website</h3>
          <p>Built a personal blog with categories, search functionality, and comment section using front-end technologies.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <div class="container">
      <h2>Contact Me</h2>
      <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <!-- Resume Download Section -->
  <section id="resume-download">
    <div class="container">
      <h2>Download My Resume</h2>
      <p>Click the button below to download my resume in PDF format.</p>
      <a href="hariharan-resume.pdf" download="Hariharan-Resume.pdf">
        <button>Download Resume</button>
      </a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2023 Hariharan. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>
