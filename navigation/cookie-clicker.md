---
layout: page
permalink: /cookie/
title:  
toc: true
comments: false
---
 
 <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background-color: #f3f4f6;
    }
    #cookie {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      background-color: #e07a5f;
      border: 5px solid #3d405b;
      cursor: pointer;
    }
    #score {
      font-size: 2em;
      margin: 20px;
    }
  </style>

  <h1>Cookie Clicker</h1>
  <p id="score">Cookies: 0</p>
  <div id="cookie"></div>

  <script>
    let score = 0;
    const cookie = document.getElementById('cookie');
    const scoreDisplay = document.getElementById('score');

    cookie.addEventListener('click', function () {
      score++;
      scoreDisplay.textContent = `Cookies: ${score}`;
    });
  </script>

  <div class="sidebar">
  <h2>Games Menu</h2>
  <ul class="menu-list">
    <li><a href="https://dakshag001.github.io/dakshaggCSP_2025/snake/" target="_blank">Snake</a></li>
    <li><a href="https://dakshag001.github.io/dakshaggCSP_2025/cookie/" target="_blank">Cookie Clicker</a></li>
    <li><a href="https://dakshag001.github.io/dakshaggCSP_2025/calculator/" target="_blank">Calculator</a></li>
    <li><a href="https://dakshag001.github.io/dakshaggCSP_2025/Dinoo/" target="_blank">WIP Dino game</a></li>
  </ul>
</div>

<style>
  /* Sidebar container styling */
  .sidebar {
    width: 200px;
    background-color: #333;
    color: white;
    position: fixed;
    top: 0;
    left: 0;
    height: 100vh; /* Full height */
    padding: 20px;
    box-shadow: 2px 0 5px rgba(0, 0, 0, 0.5);
  }

  /* Heading style inside the sidebar */
  .sidebar h2 {
    margin-top: 0;
    font-size: 24px;
    text-align: center;
  }

  /* Menu list styling */
  .menu-list {
    list-style: none;
    padding: 0;
  }

  /* Individual link items */
  .menu-list li {
    margin: 15px 0;
  }

  /* Link styles */
  .menu-list a {
    color: white;
    text-decoration: none;
    font-size: 18px;
    transition: color 0.3s;
  }

  /* Hover effect for links */
  .menu-list a:hover {
    color: #1e90ff;
  }

  /* Adjust layout when the sidebar is active */
  body {
    margin-left: 220px; /* Adjust content to avoid overlap */
    font-family: Arial, sans-serif;
  }
</style>