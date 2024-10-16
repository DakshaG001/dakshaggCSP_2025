---
layout: page
title: Sprint 2 
permalink: /Sprint2summary/
---

# Team Teach 
<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  /* Main container: 3x3 Grid */
  .main-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    margin: 20px; /* Push the grid inward by 20px from all sides */
}


  /* Each menu */
  .menu {
    width: 300px;
    border-radius: 8px;
    background-color: #333;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    overflow: hidden;
    transition: transform 0.2s; /* Add hover animation */
  }

  .menu:hover {
    transform: scale(1.05); /* Slightly enlarge on hover */
  }

  .menu-title {
    background-color: #444;
    padding: 15px;
    cursor: pointer;
    font-size: 18px;
    font-weight: bold;
    text-align: center;
    transition: background-color 0.3s;
  }

  .menu-title:hover {
    background-color: #555;
  }

  .menu-content {
    max-height: 0;
    overflow: hidden;
    background-color: #222;
    transition: max-height 0.5s ease-out;
    padding: 0 15px;
    word-wrap: break-word;
    font-size: 12px; 
}

.menu-content.open {
    max-height: 500px; /* Increase height to fit long text */
    padding: 15px;
}

</style>

<div class="main-container">
  <div class="menu">
    <div class="menu-title" onclick="toggleMenu('menuContent1')">3.1</div>
    <div class="menu-content" id="menuContent1">
      <p> - Python and Jasvascript variables. Like name = "dave" in Python. Or let name = "dave" in javascript. Variables are containers that hold info.</p>
    </div>
  </div>

  <div class="menu">
    <div class="menu-title" onclick="toggleMenu('menuContent2')">3.2</div>
    <div class="menu-content" id="menuContent2">
      <p>- Covered Basics of Data Abstraction including integers,floats, strings, lists
         tuples, dictionaries, sets and booleans. Integers are whole numbers (1,5,10). Floats are like integers except they are used for decimal points. Strings are used for repetition if you wanted to say repeat the letter O ten or multiple times. Lists are used for grouping multiple data types eg odd = ["1", "3", "5"] and then you would print it out. Tuples are likke lists but are immutable. Dictionaries are used for storaging terms, like if you had a profile you wanted to store. Sets are used for printing an unordered set of names. Booleans are used for true or false values which can be used in if else statements</p>
    </div>
  </div>

  <div class="menu">
    <div class="menu-title" onclick="toggleMenu('menuContent3')">3.3</div>
    <div class="menu-content" id="menuContent3">
      <p>A mathematical expression consists of symbols, such as numbers, variables, and operators, arranged to show a calculation or define a relationship between quantities. This is used in algorathims to solve complex problems and more with addition subtraction, etc. Such as creating a list of your values or integers and doing a mathematical calculation to then print the answer </p>
    </div>
  </div>

  <div class="menu">
    <div class="menu-title" onclick="toggleMenu('menuContent4')">3.4</div>
    <div class="menu-content" id="menuContent4">
      <p>Strings can be made using Single Quotes (‘’) Double Quotes (“”) Backticks (``). They can be used for counting number of chyaractersm, adding different strings together, or printing characters based on certain requirements, like fetching a word in a string that is from [4:10] </p>
    </div>
  </div>

  <div class="menu">
    <div class="menu-title" onclick="toggleMenu('menuContent5')">3.5</div>
    <div class="menu-content" id="menuContent5">
      <p>Booleans are only true or false, and when expressed it is either true or false. Relational operators are used for evaluating to a boolean value eg. a>b where it is true if a is greater than b or it will be false. you can use this for setting requirements numerical wise, say if you want a certain message to show for a set score say 50, you can use a boolean to do this. there is also logical operators thatr are used for multiple conditions to produce a single boolean value. This can be used for setting requirements that have multiple requirements, say they need a score of 40 to pass under 3 tries.</p>
    </div>
  </div>

  <div class="menu">
    <div class="menu-title" onclick="toggleMenu('menuContent6')">3.6</div>
    <div class="menu-content" id="menuContent6">
      <p>if else statements are used as conditionals, if a variable meets a requirement for an if statement, the output for the if statement is followed. If it doesn't, the else output is followed. An example is x=5 if x>5 print(pass) else: print(fail)</p>
    </div>
  </div>

  <div class="menu">
    <div class="menu-title" onclick="toggleMenu('menuContent7')">3.7</div>
    <div class="menu-content" id="menuContent7">
      <p>conditional are statements used for checking a true or false statement, and if it follows a true or a false, it will run code related to it. Nested conditionals are used for if or else statements if it is placed inside another if else statementm allowing for multiple sequences. You can also use these and combine true false with if and else.</p>
    </div>
  </div>

  <div class="menu">
    <div class="menu-title" onclick="toggleMenu('menuContent8')">3.8</div>
    <div class="menu-content" id="menuContent8">
      <p>For loops are used for iterating code. Loops are used for running tasks in lists or sets. This can print multiple values which is useful in many scenarios. You can also loop strings that will print out characters in a dropdown format. There are also break statements which can be used to print a variable, but disclude a value in a variable. JS loops are slightly more complex and use loops like this for (let i = 0; i < str.length; i++) { ... }. This allows to print at the starting value 0 inthe the characters all the way to the end 12 H to !. </p>
    </div>
  </div>

  <div class="menu">
    <div class="menu-title" onclick="toggleMenu('menuContent9')">Thats it!</div>
    <div class="menu-content" id="menuContent9">
      <p>nothing here siuu</p>
    </div>
  </div>
</div>

<script>
  function toggleMenu(contentId) {
    const content = document.getElementById(contentId);
    content.classList.toggle('open');
  }
</script>


<style>
.custom-button {
  min-width: 120px;

  position: relative;
  cursor: pointer;

  padding: 12px 17px;
  border: 0;
  border-radius: 7px;

  box-shadow: inset 0 0 0 1px rgba(255, 255, 255, 0.1);
  background: radial-gradient(
    ellipse at bottom,
    rgba(71, 81, 92, 1) 0%,
    rgba(11, 21, 30, 1) 45%
  );

  color: rgba(255, 255, 255, 0.66);

  transition: all 1s cubic-bezier(0.15, 0.83, 0.66, 1);
}
.custom-button::before {
  content: "";
  width: 70%;
  height: 1px;

  position: absolute;
  bottom: 0;
  left: 15%;

  background: rgb(255, 255, 255);
  background: linear-gradient(
    90deg,
    rgba(255, 255, 255, 0) 0%,
    rgba(255, 255, 255, 1) 50%,
    rgba(255, 255, 255, 0) 100%
  );
  opacity: 0.2;

  transition: all 1s cubic-bezier(0.15, 0.83, 0.66, 1);
}
.custom-button:hover {
  color: rgba(255, 255, 255, 1);
  transform: scale(1.1) translateY(-3px);
}
.custom-button:hover::before {
  opacity: 1;
}
</style>

# Summary
Variables store information, like name = "dave" in Python or let name = "dave" in JavaScript. Data types include integers, floats, strings, lists, tuples, dictionaries, sets, and booleans, each serving different purposes like grouping data or storing key-value pairs. Mathematical expressions perform calculations, and booleans help evaluate conditions with relational or logical operators. Control structures like if-else statements and loops (e.g., for loops) are used to manage the flow of code and handle repetitive tasks efficiently.

# My contribution
I focused on pseudocode which is a simplified, language-agnostic way to outline a program’s logic, focusing on the steps without strict syntax. It helps plan algorithms by breaking down tasks clearly, making it easier to translate into actual code. I created a lesson on this to showcase the purpose of psuedocode, which is pretty important because collegeboard wants you to know pseudocode. 

#### My teams 3.10 focused on using psueodocde, lists, list operations, and functions. We expanded on these elements and through our knowledge and understanding, presented it to the class for them to learn

# Big Idea Notes
<a href="https://dakshag001.github.io/dakshaggCSP_2025/2024/07/04/3_4_IPYNB_2_.html">
  <button class="button">3.1 & 3.4</button>
  </a>
<a href="https://dakshag001.github.io/dakshaggCSP_2025/2024/10/07/3_2_IPYNB_2_.html">
  <button class="button">3.2</button>
  </a>
<a href="https://dakshag001.github.io/dakshaggCSP_2025/2024/07/09/3_3_IPYNB_2_.html">
  <button class="button">3.3 & 3.5</button>
  </a>
<a href="https://dakshag001.github.io/dakshaggCSP_2025/2024/07/10/3_6_IPYNB_2_.html">
  <button class="button">3.6 & 3.7</button>
  </a>
<a href="https://dakshag001.github.io/dakshaggCSP_2025/2024/10/03/3_8_IPYNB_2_.html">
  <button class="button">3.8</button>
  </a>
  
# Game progress on the left <-
- added a sidebar to showcase all games

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

<style>
button {
 appearance: button;
 background-color: #1899D6;
 border: solid transparent;
 border-radius: 16px;
 border-width: 0 0 4px;
 box-sizing: border-box;
 color: #FFFFFF;
 cursor: pointer;
 display: inline-block;
 font-size: 15px;
 font-weight: 700;
 letter-spacing: .8px;
 line-height: 20px;
 margin: 0;
 outline: none;
 overflow: visible;
 padding: 13px 19px;
 text-align: center;
 text-transform: uppercase;
 touch-action: manipulation;
 transform: translateZ(0);
 transition: filter .2s;
 user-select: none;
 -webkit-user-select: none;
 vertical-align: middle;
 white-space: nowrap;
}

button:after {
 background-clip: padding-box;
 background-color: #1CB0F6;
 border: solid transparent;
 border-radius: 16px;
 border-width: 0 0 4px;
 bottom: -4px;
 content: "";
 left: 0;
 position: absolute;
 right: 0;
 top: 0;
 z-index: -1;
}

button:main, button:focus {
 user-select: auto;
}

button:hover:not(:disabled) {
 filter: brightness(1.1);
}

button:disabled {
 cursor: auto;
}

button:active:after {
 border-width: 0 0 0px;
}

button:active {
 padding-bottom: 10px;
}
</style>


