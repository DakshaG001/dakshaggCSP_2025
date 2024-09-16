---
layout: base
title: Student Home 
description: Home Page
hide: true
---

# **My journey starts here**

<img src="images/notebooks/3810370_8caf5a9703664533b3b1cf2b4e040537_processed.jpg" alt="Image" width="25%">

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
<!-- coding for 3 buttons -->
<a href="https://nighthawkcoders.github.io/portfolio_2025/navigation/section/csp">
  <button class="custom-button">Nighthawk Pages</button>
</a>
<a href="https://dakshag001.github.io/dakshaggCSP_2025/blogs/">
  <button class="custom-button">Blogs</button>
</a>
<a href="https://dakshag001.github.io/dakshaggCSP_2025/search/">
  <button class="custom-button">Search</button>
</a>
<!-- styling for menu -->





<style>
   .paste-button {
    position: relative;
    display: block;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.paste-button .button {
    padding: 1.3em 3em;
    font-size: 12px;
    text-transform: uppercase;
    letter-spacing: 2.5px;
    font-weight: 500;
    color: #000;
    background-color: #fff;
    border: none;
    border-radius: 45px;
    box-shadow: 0px 8px 15px rgba(0, 0, 0, 0.1);
    transition: all 0.3s ease 0s;
    cursor: pointer;
    outline: none;
    display: flex;
    align-items: center;
    justify-content: center;
}

.paste-button .button:hover {
    background-color: #23c483;
    box-shadow: 0px 15px 20px rgba(46, 229, 157, 0.4);
    color: #fff;
    transform: translateY(-7px);
}

.paste-button .button:active {
    transform: translateY(-1px);
}

.dropdown-content, .submenu-content {
    display: none;
    font-size: 13px;
    position: absolute;
    z-index: 1;
    min-width: 200px;
    background-color: #212121;
    border: 2px solid #88bc4c;
    border-radius: 0px 15px 15px 15px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
}

.dropdown-content a, .submenu-content a {
    color: #88bc4c;
    padding: 8px 10px;
    text-decoration: none;
    display: block;
    transition: 0.1s;
}

.dropdown-content a:hover, .submenu-content a:hover {
    background-color: #88bc4c;
    color: #212121;
}

.dropdown-content a:focus, .submenu-content a:focus {
    background-color: #212121;
    color: #88bc4c;
}

.dropdown-content #top:hover {
    border-radius: 0px 13px 0px 0px;
}

.dropdown-content #bottom:hover {
    border-radius: 0px 0px 13px 13px;
}

.paste-button:hover .button {
    border-radius: 15px 15px 0px 0px;
}

.paste-button:hover .dropdown-content {
    display: block;
}

.submenu {
    position: relative;
}

.submenu-content {
    top: 0;
    left: 100%;
    border-radius: 0 15px 15px 15px;
}

.submenu-content a:first-child:hover {
    border-radius: 0px 13px 0px 0px;
}

.submenu-content a:last-child:hover {
    border-radius: 0px 0px 13px 13px;
}

.submenu:hover .submenu-content {
    display: block;
}

</style>
<!-- code for menu -->
<div class="paste-button">
  <button class="button">Menu &nbsp; ▼</button>
  <div class="dropdown-content">
    <a id="top" href="https://dakshag001.github.io/dakshaggCSP_2025/2024/09/08/JavaScriptCell_IPYNB_2_.html">JavaScript Cell</a>
    <div class="submenu">
        <a id="middle" href="https://dakshag001.github.io/dakshaggCSP_2025/2024/08/21/sprint1_plan_IPYNB_2_.html">Plans &nbsp; ▶</a>
        <div class="submenu-content">
            <a href="https://dakshag001.github.io/dakshaggCSP_2025/2024/09/12/PlanningFolder_IPYNB_2_.html">Attempts</a>
            <a href="https://example.com/">Finalized Project stuff</a>
        </div>
    </div>
    <a id="bottom" href="https://dakshag001.github.io/dakshaggCSP_2025/about/">About Pages</a>
  </div>
</div>
<!-- end of menu code -->


