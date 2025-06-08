<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Akhilesh U - Profile</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: "Segoe UI", sans-serif;
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .profile-card {
      background: #1e1e2f;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
      text-align: center;
      width: 350px;
      transition: transform 0.3s ease-in-out;
    }

    .profile-card:hover {
      transform: scale(1.05);
    }

    h1 {
      font-size: 2em;
      margin: 10px 0;
      color: #00ffe7;
    }

    .tagline {
      font-size: 1.2em;
      color: #ccc;
      margin-bottom: 20px;
    }

    .info {
      text-align: left;
      margin-top: 20px;
      font-size: 0.95em;
    }

    .info span {
      display: block;
      margin: 5px 0;
    }

    .skills {
      margin-top: 20px;
    }

    .skill-tag {
      display: inline-block;
      background-color: #00ffe7;
      color: #000;
      border-radius: 15px;
      padding: 5px 12px;
      margin: 5px;
      font-weight: bold;
    }

    .contact-btn {
      margin-top: 25px;
      padding: 10px 20px;
      background-color: #00ffe7;
      color: #000;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-weight: bold;
      transition: background 0.3s;
    }

    .contact-btn:hover {
      background-color: #00ccbb;
    }
  </style>
</head>
<body>
  <div class="profile-card">
    <h1>Akhilesh U</h1>
    <div class="tagline">IIT Bombay Student (2023 - 2027)</div>
    
    <div class="info">
      <span><strong>📍 Location:</strong> Bangalore, Karnataka</span>
      <span><strong>📞 Phone:</strong> 6363027032</span>
      <span><strong>✉️ Email:</strong> akhilesh2777u@gmail.com</span>
    </div>

    <div class="skills">
      <div class="skill-tag">Java</div>
      <div class="skill-tag">Python</div>
      <div class="skill-tag">HTML</div>
      <div class="skill-tag">CSS</div>
    </div>

    <button class="contact-btn" onclick="sayHello()">Say Hello 👋</button>
  </div>

  <script>
    function sayHello() {
      alert("Hey there! I'm Akhilesh, nice to meet you 👋😊");
    }
  </script>
</body>
</html>
