# Portfolio
<!DOCTYPE html>
<html>
<head>
    <title>Personal Portfolio</title>
    <style>
        body {
            font-family: "Montserrat", sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f5f5f5;
            color: #333;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 16px;
        }
        .sidebar {
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            background-image: url('one1.jpg');
            min-height: 100vh;
            width: 40%;
            position: fixed;
            top: 0;
            left: 0;
        }
        .content {
            margin-left: 40%;
            padding: 16px;
        }
        .menu-icon {
            position: fixed;
            top: 16px;
            right: 16px;
            font-size: 24px;
            cursor: pointer;
            color: #333;
        }
        .sidebar-hidden {
            display: none;
        }
        .header {
            text-align: center;
            padding: 128px 16px;
        }
        .header h1 {
            margin-bottom: 8px;
            font-size: 36px;
        }
        .header h2 {
            margin-bottom: 16px;
            font-size: 24px;
            color: #666;
        }
        .header p {
            color: #888;
        }
        .section {
            padding: 32px 16px;
            background-color: #fff;
            border-radius: 8px;
            margin-bottom: 16px;
        }
        .section h2 {
            margin-bottom: 16px;
            color: #333;
            font-size: 24px;
        }
        .section hr {
            border-top: 1px solid #ccc;
        }
        .form-group {
            margin-bottom: 16px;
        }
        label {
            font-weight: bold;
            color: #333;
        }
        input[type="text"],
        input[type="email"],
        textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
            margin-bottom: 16px;
        }
        button {
            background-color: #007bff;
            color: #fff;
            border: none;
            padding: 12px 24px;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #0056b3;
        }
        .contact-info {
            text-align: center;
            margin-top: 32px;
            color: #666;
        }
    </style>
</head>
<body>

<nav class="sidebar"></nav>


<div class="content">
  <span class="menu-icon" onclick="openNav()"><i class="fa fa-bars"></i></span>
  <header class="header" id="home">
    <h1>Abdullah Malik</h1>
    <h2>Web Developer</h2>
    <p>Crafting beautiful and functional web experiences</p>
  </header>

  <div class="section" id="education">
    <h2>Education</h2> <hr>
    <ul>
        <li><strong>BS in Computer Science</strong> - University of Management and Technology</li>
        <li><strong>High School Diploma</strong> - Beachonhouse School System</li>
    </ul>
  </div>
  <div class="section" id="skills">
    <h2>Skills</h2>
    <hr>
    <p>HTML, CSS, JavaScript</p>
    <div style="background-color:lightgrey">
      <div style="background-color:grey; width:90%; padding:8px; color:white">90%</div>
    </div>
    <p>React, Angular</p>
    <div style="background-color:lightgrey">
      <div style="background-color:grey; width:85%; padding:8px; color:white">85%</div>
    </div>
    <p>Node.js, Express</p>
    <div style="background-color:lightgrey">
      <div style="background-color:grey; width:80%; padding:8px; color:white">80%</div>
    </div>
  </div>

  <div class="section" id="experience">
    <h2>Experience</h2><hr>
    <ul>
        <li><strong>Front-end Developer</strong> at Tech Solutions Inc.</li>
        <li><strong>Intern</strong> at Web Innovations LLC.</li>
    </ul>
  </div>

  <div class="section" id="projects">
    <h2>Complete Projects</h2><hr>
    <ul>
        <li><strong>Portfolio Website</strong> - A personal portfolio website to showcase my skills and projects.</li>
        <li><strong>E-commerce Website</strong> - A fully functional e-commerce website built with React and Node.js.</li>
    </ul>
  </div>


<div class="section" id="contact" style="background-color: #fff; padding: 32px; border-radius: 8px; margin-bottom: 16px;">
    <h2 style="margin-bottom: 16px; color: #333; font-size: 24px;">Contact Me</h2>
    <hr style="border-top: 1px solid #ccc; margin-bottom: 16px;">
    <form role="form">
        <div class="form-group" style="margin-bottom: 16px;">
            <label for="name" style="font-weight: bold; color: #333;">Name</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name" style="width: 100%; padding: 12px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box;">
        </div>
        <div class="form-group" style="margin-bottom: 16px;">
            <label for="email" style="font-weight: bold; color: #333;">Email</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email" style="width: 100%; padding: 12px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box;">
        </div>
        <div class="form-group" style="margin-bottom: 16px;">
            <label for="message" style="font-weight: bold; color: #333;">Message</label>
            <textarea id="message" rows="5" class="form-control" placeholder="Enter your message" style="width: 100%; padding: 12px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box; resize: vertical;"></textarea>
        </div>
        <button type="submit" class="btn" style="background-color: grey; color: white; border: none; padding: 12px 24px; border-radius: 4px; cursor: pointer; font-size: 16px; transition: background-color 0.3s ease;">Submit</button>
    </form>
</div>
