---
layout: page
permalink: /calculator/
title: Calculator v2.0   
toc: true
comments: false
---


<div id="calculator">
  <div id="animation">
    <div class="calculator-container">
      <div class="calculator-output" id="output">0</div>
      <div class="calculator-number">1</div>
      <div class="calculator-number">2</div>
      <div class="calculator-number">3</div>
      <div class="calculator-operation">+</div>
      <div class="calculator-number">4</div>
      <div class="calculator-number">5</div>
      <div class="calculator-number">6</div>
      <div class="calculator-operation">-</div>
      <div class="calculator-number">7</div>
      <div class="calculator-number">8</div>
      <div class="calculator-number">9</div>
      <div class="calculator-operation">*</div>
      <div class="calculator-clear">A/C</div>
      <div class="calculator-number">0</div>
      <div class="calculator-number">.</div>
      <div class="calculator-equals">=</div>
    </div>
  </div>
</div>

<style>
  #calculator {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: #F0F0F0;
    margin: 0;
  }
  #animation {
    position: relative;
    width: 100%;
    height: 100%;
  }
  .calculator-container {
    display: grid;
    grid-template-columns: repeat(4, 80px);
    grid-gap: 10px;
    background: #333;
    border-radius: 15px;
    padding: 15px;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
  .calculator-output {
    grid-column: span 4;
    background: #222;
    color: #fff;
    border-radius: 10px;
    padding: 15px;
    font-size: 24px;
    text-align: right;
    border: 2px solid #444;
  }
  .calculator-number, .calculator-operation, .calculator-clear, .calculator-equals {
    background: #444;
    color: #fff;
    border-radius: 8px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 20px;
    cursor: pointer;
    transition: background 0.3s;
  }
  .calculator-number:hover, .calculator-operation:hover, .calculator-clear:hover, .calculator-equals:hover {
    background: #555;
  }
  .calculator-clear {
    grid-column: span 2;
    background: #E74C3C;
  }
  .calculator-equals {
    grid-column: span 2;
    background: #2ECC71;
  }
</style>

<script>
// JavaScript code remains the same
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