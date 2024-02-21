<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sanjib's Profile</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f2f5;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 800px;
      margin: 50px auto;
      padding: 20px;
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      overflow: hidden;
    }

    .header {
      text-align: center;
      margin-bottom: 20px;
    }

    .header h1 {
      font-size: 36px;
      margin-bottom: 5px;
      color: #333;
    }

    .header h3 {
      font-size: 18px;
      color: #666;
    }

    .profile-img {
      border-radius: 50%;
      margin-left: 20px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
      animation: float 3s ease-in-out infinite;
    }

    @keyframes float {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-10px);
      }
    }

    .content {
      display: flex;
      align-items: center;
    }

    .info {
      flex: 1;
    }

    .info p {
      margin-bottom: 10px;
      color: #555;
    }

    .social-icons {
      display: flex;
      justify-content: center;
      margin-top: 20px;
    }

    .social-icons a {
      margin: 0 10px;
      transition: transform 0.3s ease;
    }

    .social-icons a:hover {
      transform: scale(1.2);
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <h1>Hi 👋, I'm Sanjib</h1>
      <h3>A passionate Jr Programmer from India</h3>
    </div>
    <div class="content">
      <img class="profile-img" alt="coding" width="150" src="https://i.pinimg.com/originals/74/5c/c9/745cc90fcc688569610f84bc5d2b2fd6.gif">
      <div class="info">
        <p><strong>🔭 Currently working on:</strong> <a href="https://glitch.com/edit/#!/marred-fierce-bronze">AR Project's</a></p>
        <p><strong>🌱 Currently learning:</strong> AR, Flutter, Robo Biotics</p>
        <p><strong>💬 Ask me about:</strong> React, Expo React-Native, Python, VR</p>
        <p><strong>⚡ Fun fact:</strong> I Am A Lazy</p>
        <div class="social-icons">
          <a href="https://codepen.io/sanjibmaity2022" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/codepen.svg" alt="codepen"></a>
          <a href="https://www.linkedin.com/in/sanjib-maity-a450432b6/" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="linkedin"></a>
          <a href="https://www.instagram.com/jr_programer_sanjib/" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="instagram"></a>
        </div>
      </div>
    </div>
  </div>
</body>
</html>
