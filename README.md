<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Details</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }

    .container {
      max-width: 800px;
      margin: 20px auto;
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .header-image {
      text-align: center;
      margin-bottom: 20px;
    }

    .header-image img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
    }

    h1 {
      text-align: center;
      color: #007acc;
    }

    h2 {
      margin-top: 20px;
      color: #444;
    }

    p {
      margin: 10px 0;
    }

    .btn {
      display: inline-block;
      margin: 10px 5px;
      padding: 10px 15px;
      background: #007acc;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
      transition: background 0.3s;
    }

    .btn:hover {
      background: #005f99;
    }

    .social-icons {
      text-align: center;
      margin: 20px 0;
    }

    .social-icons a {
      margin: 0 10px;
      text-decoration: none;
      color: #007acc;
      font-size: 20px;
    }

    .social-icons a:hover {
      color: #005f99;
    }

    .code-block {
      background: #f9f9f9;
      border-left: 4px solid #007acc;
      padding: 10px;
      margin: 10px 0;
      font-family: monospace;
      overflow-x: auto;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header-image">
      <img src="https://via.placeholder.com/800x200" alt="Header Image">
    </div>
    <h1>Welcome to My GitHub Profile</h1>
    <p>Hello! I'm a passionate developer who loves building web applications and exploring new technologies. Feel free to explore my repositories and projects below.</p>
    
    <h2>Skills</h2>
    <ul>
      <li>Frontend: HTML, CSS, JavaScript, React</li>
      <li>Backend: Node.js, Express, Python</li>
      <li>Database: MySQL, MongoDB</li>
      <li>Tools: Git, Docker, VS Code</li>
    </ul>
    
    <h2>Projects</h2>
    <div class="code-block">
      <p><strong>Project Name:</strong> My Awesome App</p>
      <p><strong>Description:</strong> A simple and user-friendly app for managing tasks.</p>
      <p><strong>GitHub Repo:</strong> <a href="https://github.com/username/my-awesome-app" class="btn">View Repo</a></p>
    </div>

    <h2>Connect with Me</h2>
    <div class="social-icons">
      <a href="https://twitter.com/yourusername" target="_blank"><i class="fab fa-twitter"></i></a>
      <a href="https://linkedin.com/in/yourusername" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="https://github.com/yourusername" target="_blank"><i class="fab fa-github"></i></a>
    </div>
  </div>
</body>
</html>
