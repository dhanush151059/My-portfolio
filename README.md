<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dhanush S Portfolio</title>
  <style>
    /* General Styles */
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      scroll-behavior: smooth;
      color: #333;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      background-color: #007b7f;
      color: white;
    }

    .logo {
      font-size: 24px;
      font-weight: bold;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
      margin: 0;
      padding: 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: 500;
    }

    nav a:hover {
      text-decoration: underline;
    }

    /* Home Section */
    .content {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      padding: 60px 20px;
      background: linear-gradient(to bottom right, #e0f7f4, #ffffff);
    }

    .image-box img {
      width: 250px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      margin-right: 40px;
    }

    .text-box {
      max-width: 500px;
    }

    .intro {
      font-size: 18px;
      color: #777;
    }

    h1 {
      font-size: 36px;
      margin: 10px 0;
    }

    .subheading {
      font-size: 20px;
      color: #007b7f;
      margin-bottom: 20px;
    }

    .buttons a {
      display: inline-block;
      margin-right: 15px;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: 500;
    }

    .btn {
      background-color: #007b7f;
      color: white;
    }

    .btn-secondary {
      background-color: #e0f7f4;
      color: #007b7f;
      border: 1px solid #007b7f;
    }

    /* About Section */
    .about-section {
      padding: 60px 40px;
      background: linear-gradient(to bottom right, #ffffff, #e0f7f4);
    }

    .about-header {
      text-align: center;
      margin-bottom: 40px;
    }

    .get-to-know {
      font-size: 16px;
      color: #777;
    }

    .about-header h2 {
      font-size: 32px;
      color: #007b7f;
    }

    .about-content {
      display: flex;
      flex-wrap: wrap;
      gap: 40px;
      justify-content: center;
    }

    .about-image img {
      width: 250px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }

    .about-boxes {
      display: flex;
      gap: 30px;
      flex-wrap: wrap;
    }

    .info-box {
      background-color: #f8f9fa;
      border: 1px solid #ccc;
      padding: 20px;
      border-radius: 10px;
      width: 250px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }

    .info-box h3 {
      text-align: center;
      font-size: 20px;
      color: #007b7f;
      margin-bottom: 15px;
    }

    .info-box p {
      font-size: 16px;
      color: #555;
      margin: 5px 0;
    }

    /* Experience Section */
    .experience-section {
      padding: 60px 20px;
      text-align: center;
      background-image: url('experience background.jpg');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
      background-attachment: fixed;
      color: #333;
    }

    .experience-section-inner {
      background-color: rgba(255, 255, 255, 0.85);
      border-radius: 12px;
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
    }

    .experience-section-inner h2 {
      font-size: 36px;
      color: #007b7f;
      margin-bottom: 40px;
    }

    .experience-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 40px;
    }

    .experience-box {
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 30px 20px;
      width: 320px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .experience-box h3 {
      font-size: 20px;
      color: #007b7f;
      margin-bottom: 20px;
    }

    .pill-group {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 12px;
    }

    .pill-item {
      background-color: #e9f5f4;
      padding: 8px 14px;
      border-radius: 20px;
      font-size: 14px;
      color: #555;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }

    .pill-item b {
      font-size: 15px;
      color: #007b7f;
      font-weight: 600;
    }

    .pill-item span {
      font-size: 13px;
      font-style: italic;
      margin-left: 6px;
    }

    @media (max-width: 768px) {
      .content, .about-content, .experience-grid {
        flex-direction: column;
        align-items: center;
      }

      .experience-box {
        width: 90%;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">DHANUSH S</div>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Home Section -->
  <main>
    <div class="content">
      <div class="image-box">
        <img src="my image .jpg" alt="Dhanush S" />
      </div>
      <div class="text-box">
        <p class="intro">Hello, I'm</p>
        <h1>DHANUSH S</h1>
        <h3 class="subheading">AZURE IAAS | Frontend Developer | <br>Active Directory Management</h3>
        <div class="buttons">
          <a href="#" class="btn">Download CV</a>
          <a href="#" class="btn btn-secondary">Contact Info</a>
        </div>
      </div>
    </div>
  </main>

  <!-- About Section -->
  <section id="about" class="about-section">
    <div class="about-header">
      <p class="get-to-know">Get to know</p>
      <h2>About Me</h2>
    </div>
    <div class="about-content">
      <div class="about-image">
        <img src="about photo.jpg" alt="Dhanush S" />
      </div>
      <div class="about-boxes">
        <div class="info-box">
          <h3>Experience</h3>
          <p><strong>2+ years</strong></p>
          <p>Frontend Development</p>
          <p><strong>1 year</strong></p>
          <p>Active Directory Management</p>
        </div>
        <div class="info-box">
          <h3>Education</h3>
          <p>B.Tech Information Technology</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Experience Section -->
  <section id="experience" class="experience-section">
    <p>Explore My</p>
    <h2>Experience</h2>

    <div class="experience-grid">

      <!-- Frontend Development Box -->
      <div class="experience-box">
        <h3>Frontend Development</h3>
        <div class="pill-group">
          <div class="pill-item"><b>HTML</b><span>– Experienced</span></div>
          <div class="pill-item"><b>CSS</b><span>– Experienced</span></div>
          <div class="pill-item"><b>SASS</b><span>– Experienced</span></div>
          <div class="pill-item"><b>JavaScript</b><span>– Basic</span></div>
          <div class="pill-item"><b>TypeScript</b><span>– Basic</span></div>
          <div class="pill-item"><b>Material UI</b><span>– Intermediate</span></div>
        </div>
      </div>

      <!-- Active Directory Box -->
      <div class="experience-box">
        <h3>Active Directory</h3>
        <div class="pill-group">
          <div class="pill-item"><b>Domain Controller</b></div>
          <div class="pill-item"><b>Authentication (Login)</b></div>
          <div class="pill-item"><b>Authorization (Access Control)</b></div>
          <div class="pill-item"><b>Group Policy</b></div>
        </div>
      </div>

    </div>
  </section>
  <section id="contact" style="padding: 60px 40px; background-color: #f4fdfd; font-family: 'Segoe UI', sans-serif;">
  <div style="max-width: 1000px; margin: auto; display: flex; flex-wrap: wrap; gap: 40px; justify-content: center;">
    
    <!-- Contact Info -->
    <div style="flex: 1; min-width: 280px;">
      <h2 style="color: #007b7f; font-size: 32px; margin-bottom: 20px;">Let's Connect</h2>
      <p style="color: #555; font-size: 16px; margin-bottom: 30px;">
        Whether you have a project in mind, want to collaborate, or just say hi — I’d love to hear from you.
      </p>
      <div style="line-height: 1.8;">
        <p><strong>Email:</strong> <a href="mailto:dhanush@example.com" style="color: #007b7f;">dhanush@example.com</a></p>
        <p><strong>Phone:</strong> <a href="tel:+919876543210" style="color: #007b7f;">+91 98765 43210</a></p>
        <p><strong>Location:</strong> Madurai, Tamil Nadu</p>
        <p><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/dhanush" target="_blank" style="color: #007b7f;">linkedin.com/in/dhanush</a></p>
      </div>
    </div>

    <!-- Contact Form -->
    <div style="flex: 1; min-width: 280px;">
      <form style="background-color: #ffffff; padding: 30px; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
        <div style="margin-bottom: 20px;">
          <label style="display: block; font-weight: 500; margin-bottom: 6px;">Your Name</label>
          <input type="text" placeholder="Enter your name" required
            style="width: 100%; padding: 10px 14px; border: 1px solid #ccc; border-radius: 6px;" />
        </div>
        <div style="margin-bottom: 20px;">
          <label style="display: block; font-weight: 500; margin-bottom: 6px;">Email Address</label>
          <input type="email" placeholder="you@example.com" required
            style="width: 100%; padding: 10px 14px; border: 1px solid #ccc; border-radius: 6px;" />
        </div>
        <div style="margin-bottom: 20px;">
          <label style="display: block; font-weight: 500; margin-bottom: 6px;">Message</label>
          <textarea rows="5" placeholder="Type your message..." required
            style="width: 100%; padding: 10px 14px; border: 1px solid #ccc; border-radius: 6px;"></textarea>
        </div>
        <button type="submit"
          style="background-color: #007b7f; color: white; padding: 10px 20px; border: none; border-radius: 6px; font-weight: 500; cursor: pointer;">
          Send Message
        </button>
      </form>
    </div>
  </div>
</section><img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1c83d8ad-804c-43c2-bb3e-e6252c070d70" />
