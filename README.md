<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Md Razib Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f0f2f5;
      color: #333;
    }

    .container {
      max-width: 600px;
      margin: 0 auto;
      padding: 30px 20px;
      background: #fff;
    }

    .profile {
      text-align: center;
      padding-bottom: 30px;
      border-bottom: 1px solid #ddd;
    }

    .profile img {
      width: 130px;
      height: 130px;
      border-radius: 50%;
      border: 3px solid #1a1a1a;
      padding-top:20px
      object-fit: cover;
    }

    .profile h1 {
      margin: 15px 0 5px;
      font-size: 28px;
      color: #1a1a1a;
    }

    .profile p {
      font-size: 15px;
      color: #555;
      line-height: 1.6;
      padding: 0 10px;
    }

    .profile a {
      display: inline-block;
      margin-top: 15px;
      color: #00bcd4;
      text-decoration: none;
      font-size: 14px;
    }

    .section-title {
      font-size: 22px;
      margin: 30px 0 15px;
      border-left: 4px solid #1a1a1a;
      padding-left: 10px;
      color: #1a1a1a;
    }

    .projects {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }

    .project-card {
      background: #fafafa;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
      transition: 0.3s;
    }

    .project-card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .project-card .content {
      padding: 15px;
    }

    .project-card h3 {
      margin: 0;
      font-size: 18px;
      color: #1a1a1a;
    }

    footer {
      text-align: center;
      margin: 40px 0 20px;
      font-size: 14px;
      color: #888;
    }

    @media (max-width: 600px) {
      .container {
        padding: 20px 15px;
      }

      .project-card img {
        height: 160px;
      }
    }
  </style>
</head>
<body>

<div class="container">
  <!-- Profile Section -->
  <div class="profile">
    <img src="https://i.postimg.cc/tg3L1R50/rfereg-copy.jpg" alt="Md Razib">
    <h1>Md Razib</h1>
    <p>Creative Developer & Designer. Passionate about clean UI, web performance, and creating meaningful digital experiences.</p>
    <a href="#projects">View Projects ↓</a>
  </div>

  <!-- Projects -->
  <div id="projects">
    <div class="section-title">My Projects</div>
    <div class="projects">
      <div class="project-card">
        <img src="https://i.postimg.cc/VLwVBwzp/Screenshot-20250721-112818-1.png" alt="Project 1">
        <div class="content">
          <h3>Email Signature 1</h3>
        </div>
      </div>

      <div class="project-card">
        <img src="https://i.postimg.cc/RVvHLsyX/Screenshot-20250721-112958-1.png" alt="Project 2">
        <div class="content">
          <h3>Email Signature 2</h3>
        </div>
      </div>

      <div class="project-card">
        <img src="https://i.postimg.cc/cHZs9GTt/Screenshot-20250721-112925-1.png" alt="Project 3">
        <div class="content">
          <h3>Email Signature 3</h3>
        </div>
      </div>
    </div>
  </div>
</div>

<footer>
  &copy; 2025 Md Razib. All Rights Reserved.
</footer>

</body>
</html>
