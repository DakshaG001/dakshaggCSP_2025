---
layout: page
title: Dino Game
permalink: /Dinoo/
---

<div class="gameContainer">
  <div class="player"></div>
</div>

<style>
  .gameContainer {
    display: flex;
    justify-content: center;
    align-items: flex-end;
    height: 100vh;
    background-color: #f0f0f0;
    margin: 0;
    overflow: hidden;
    position: relative;
  }

  /* Game area */
  .game {
    position: relative;
    width: 800px;
    height: 200px;
    background-color: #fff;
    border: 2px solid #333;
    overflow: hidden;
  }

  /* Player (our "dino") */
  .player {
    position: absolute;
    bottom: 0;
    left: 50px;
    width: 30px;
    height: 30px;
    background-color: #4CAF50;
  }

  /* Obstacle */
  .obstacle {
    position: absolute;
    bottom: 0;
    right: 0;
    width: 20px;
    height: 30px;
    background-color: #f44336;
  }
</style>

<script>
  const player = document.querySelector('.player');
  const gameContainer = document.querySelector('.gameContainer');
  let isJumping = false;
  let score = 0;

  // Function to create an obstacle
  function createObstacle() {
    const obstacle = document.createElement('div');
    obstacle.classList.add('obstacle');
    gameContainer.appendChild(obstacle);
    
    let obstaclePosition = 800; // Start from the right side of the game container
    let randomHeight = Math.random() * 70 + 30; // Random height for the obstacle
    obstacle.style.height = randomHeight + 'px';

    const obstacleTimer = setInterval(() => {
      if (obstaclePosition < -20) {
        clearInterval(obstacleTimer);
        gameContainer.removeChild(obstacle);
        score++;
        console.log("Score: " + score); // Print score to the console
      } else if (obstaclePosition > 50 && obstaclePosition < 100 && !isJumping) {
        clearInterval(obstacleTimer);
        alert("Game Over! Final Score: " + score); // Show game over alert
      } else {
        obstaclePosition -= 10; // Move the obstacle to the left
        obstacle.style.right = obstaclePosition + 'px';
      }
    }, 20);
  }

  // Jump function
  function jump() {
    if (isJumping) return;
    isJumping = true;

    let jumpHeight = 0;
    const jumpTimer = setInterval(() => {
      if (jumpHeight >= 100) {
        clearInterval(jumpTimer);
        // Fall down
        const fallTimer = setInterval(() => {
          if (jumpHeight <= 0) {
            clearInterval(fallTimer);
            isJumping = false;
          } else {
            jumpHeight -= 5;
            player.style.bottom = jumpHeight + 'px';
          }
        }, 20);
      } else {
        jumpHeight += 5;
        player.style.bottom = jumpHeight + 'px';
      }
    }, 20);
  }

  // Event listener for jump on space bar press
  document.addEventListener('keydown', (event) => {
    if (event.code === 'Space') {
      jump();
    }
  });

  // Create obstacles every 2 seconds
  setInterval(createObstacle, 2000);
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