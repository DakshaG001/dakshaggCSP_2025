---
layout: base
title: Student Home 
description: Home Page
hide: true
---

 <div class="button-container">
  <a href="https://dakshag001.github.io/dakshaggCSP_2025/" target="_blank">
    <button class="button33">
      <svg xmlns="https://dakshag001.github.io/dakshaggCSP_2025/" width="1em" height="1em" viewBox="0 0 1024 1024" stroke-width="0" fill="currentColor" stroke="currentColor" class="icon">
        <path d="M946.5 505L560.1 118.8l-25.9-25.9a31.5 31.5 0 0 0-44.4 0L77.5 505a63.9 63.9 0 0 0-18.8 46c.4 35.2 29.7 63.3 64.9 63.3h42.5V940h691.8V614.3h43.4c17.1 0 33.2-6.7 45.3-18.8a63.6 63.6 0 0 0 18.7-45.3c0-17-6.7-33.1-18.8-45.2zM568 868H456V664h112v204zm217.9-325.7V868H632V640c0-22.1-17.9-40-40-40H432c-22.1 0-40 17.9-40 40v228H238.1V542.3h-96l370-369.7 23.1 23.1L882 542.3h-96.1z"></path>
      </svg>
    </button>
  </a>
  
  <a href="https://dakshag001.github.io/dakshaggCSP_2025/search/" target="_blank">
    <button class="button33">
      <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" aria-hidden="true" viewBox="0 0 24 24" stroke-width="2" fill="none" stroke="currentColor" class="icon">
        <path d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" stroke-linejoin="round" stroke-linecap="round"></path>
      </svg>
    </button>
  </a>
  
  <a href="https://dakshag001.github.io/dakshaggCSP_2025/about/" target="_blank">
    <button class="button33">
      <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24" stroke-width="0" fill="currentColor" stroke="currentColor" class="icon">
        <path d="M12 2.5a5.5 5.5 0 0 1 3.096 10.047 9.005 9.005 0 0 1 5.9 8.181.75.75 0 1 1-1.499.044 7.5 7.5 0 0 0-14.993 0 .75.75 0 0 1-1.5-.045 9.005 9.005 0 0 1 5.9-8.18A5.5 5.5 0 0 1 12 2.5ZM8 8a4 4 0 1 0 8 0 4 4 0 0 0-8 0Z"></path>
      </svg>
    </button>
  </a>
  
  <a href="https://dakshag001.github.io/dakshaggCSP_2025/blogs/" target="_blank">
    <button class="button33">
     <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24" fill="currentColor" class="icon">
    <path d="M3 2C2.44772 2 2 2.44772 2 3V21C2 21.5523 2.44772 22 3 22H21C21.5523 22 22 21.5523 22 21V3C22 2.44772 21.5523 2 21 2H3ZM12 19L5 15H7V10H17V15H19L12 19ZM12 4C16.4183 4 20 7.58172 20 12C20 16.4183 16.4183 20 12 20C7.58172 20 4 16.4183 4 12C4 7.58172 7.58172 4 12 4Z"></path>
    </svg>
  </button>
  </a>
</div>
sz
# **This is my journey into coding**

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



# Sprints and Projects


<a href="https://nighthawkcoders.github.io/portfolio_2025/csp/big-idea/p2/3-10-2">
  <button class="custom-button">3.10 Pseudocode</button>
  </a>
  <a href="https://dakshag001.github.io/dakshaggCSP_2025/Sprint2summary/">
  <button class="custom-button">Sprint 2</button>
  </a>

<style>
.button-container {
  display: flex;
  background-color: rgba(245, 73, 144);
  width: 250px;
  height: 40px;
  align-items: center;
  justify-content: space-around;
  border-radius: 10px;
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px,
        rgba(245, 73, 144, 0.5) 5px 10px 15px;
}

.button33 {
  outline: 0 !important;
  border: 0 !important;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  background-color: transparent;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  transition: all ease-in-out 0.3s;
  cursor: pointer;
}

.button:hover {
  transform: translateY(-3px);
}

.icon {
  font-size: 20px;
}
</style>




