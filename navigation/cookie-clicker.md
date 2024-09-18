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