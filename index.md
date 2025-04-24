---
layout: base
title: Student Home 
description: Home Page
hide: true
---

<div class="snowflake-container"></div>

<div class="hero-section">
  <div class="hero-content">
    <h1 class="main-title">Daksha's Coding Journey</h1>
    <p class="subtitle">Exploring the world of computer science one project at a time</p>
    
    <div class="nav-buttons">
      <a href="https://dakshag001.github.io/dakshaggCSP_2025/" class="nav-button">
        <i class="fas fa-home"></i>
        <span>Home</span>
      </a>
      <a href="https://dakshag001.github.io/dakshaggCSP_2025/search/" class="nav-button">
        <i class="fas fa-search"></i>
        <span>Search</span>
      </a>
      <a href="https://dakshag001.github.io/dakshaggCSP_2025/about/" class="nav-button">
        <i class="fas fa-user"></i>
        <span>About</span>
      </a>
      <a href="https://dakshag001.github.io/dakshaggCSP_2025/blogs/" class="nav-button">
        <i class="fas fa-blog"></i>
        <span>Blog</span>
      </a>
    </div>
  </div>
</div>

<div class="profile-section">
  <div class="profile-image">
    <img src="images/notebooks/3810370_8caf5a9703664533b3b1cf2b4e040537_processed.jpg" alt="Profile Image">
  </div>
  <div class="profile-info">
    <h2>Featured Projects</h2>
    <div class="project-buttons">
      <a href="https://nighthawkcoders.github.io/portfolio_2025/csp/big-idea/p2/3-10-2" class="project-button">
        <span class="project-name">3.10 Pseudocode</span>
        <span class="project-desc">College Board Topics</span>
      </a>
      <a href="https://dakshag001.github.io/dakshaggCSP_2025/Sprint2summary/" class="project-button">
        <span class="project-name">Sprint 2</span>
        <span class="project-desc">Project Highlights</span>
      </a>
      <a href="{{site.baseurl}}/tri2/" class="project-button">
        <span class="project-name">Trimester 2 Final</span>
        <span class="project-desc">Final Showcase</span>
      </a>
    </div>
  </div>
</div>

<div class="menu-section">
  <h2>Project Navigator</h2>
  <div class="menu-grid">
    <a href="https://dakshag001.github.io/dakshaggCSP_2025/2024/09/08/JavaScriptCell_IPYNB_2_.html" class="menu-card">
      <i class="fab fa-js"></i>
      <span>JavaScript Cell</span>
    </a>
    <a href="https://dakshag001.github.io/dakshaggCSP_2025/2024/08/21/sprint1_plan_IPYNB_2_.html" class="menu-card">
      <i class="fas fa-tasks"></i>
      <span>Sprint Plans</span>
    </a>
    <a href="https://dakshag001.github.io/dakshaggCSP_2025/2024/09/12/PlanningFolder_IPYNB_2_.html" class="menu-card">
      <i class="fas fa-clipboard-list"></i>
      <span>Project Attempts</span>
    </a>
    <a href="https://dakshag001.github.io/dakshaggCSP_2025/study/" class="menu-card">
      <i class="fas fa-book"></i>
      <span>Study Materials</span>
    </a>
  </div>
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const snowflakeContainer = document.querySelector('.snowflake-container');
  const snowflakeCount = 100;

  // Create snowflakes
  for (let i = 0; i < snowflakeCount; i++) {
    createSnowflake();
  }

  function createSnowflake() {
    const snowflake = document.createElement('div');
    snowflake.classList.add('snowflake');
    
    // Random properties
    const size = Math.random() * 5 + 2;
    const left = Math.random() * 100;
    const animationDuration = Math.random() * 10 + 5;
    const opacity = Math.random() * 0.7 + 0.3;
    
    snowflake.style.width = `${size}px`;
    snowflake.style.height = `${size}px`;
    snowflake.style.left = `${left}%`;
    snowflake.style.animationDuration = `${animationDuration}s`;
    snowflake.style.opacity = opacity;
    
    snowflakeContainer.appendChild(snowflake);
    
    // Remove snowflake after it falls
    setTimeout(() => {
      snowflake.remove();
      createSnowflake();
    }, animationDuration * 1000);
  }
});
</script>

<style>
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

body {
  font-family: 'Poppins', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #0a0a0a;
  color: #eee;
  position: relative;
  min-height: 100vh;
  overflow-x: hidden;
}

/* Snowflakes */
.snowflake-container {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 1;
}

.snowflake {
  position: absolute;
  top: -10px;
  background-color: #fff;
  border-radius: 50%;
  opacity: 0.7;
  animation: fall linear forwards;
}

@keyframes fall {
  0% {
    transform: translateY(0) rotate(0deg);
  }
  100% {
    transform: translateY(100vh) rotate(360deg);
  }
}

.hero-section {
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background: transparent;
  color: #fff;
  text-align: center;
  position: relative;
  z-index: 2;
}

.hero-section::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: radial-gradient(circle at center, rgba(50, 50, 70, 0.4) 0%, rgba(10, 10, 10, 0.9) 100%);
  z-index: -1;
}

.hero-content {
  max-width: 800px;
  padding: 2rem;
  background: rgba(0, 0, 0, 0.6);
  backdrop-filter: blur(10px);
  border-radius: 20px;
  box-shadow: 0 0 30px rgba(255, 255, 255, 0.1);
}

.main-title {
  font-size: 3.5rem;
  margin-bottom: 1rem;
  background: linear-gradient(45deg, #4facfe 0%, #00f2fe 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  text-shadow: 0 0 10px rgba(79, 172, 254, 0.3);
}

.subtitle {
  font-size: 1.5rem;
  margin-bottom: 2rem;
  color: #bbb;
}

.nav-buttons {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 1rem;
  margin-top: 2rem;
}

.nav-button {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.75rem 1.5rem;
  background-color: rgba(255, 255, 255, 0.1);
  color: #fff;
  border-radius: 10px;
  text-decoration: none;
  transition: all 0.3s ease;
  backdrop-filter: blur(5px);
  border: 1px solid rgba(255, 255, 255, 0.05);
}

.nav-button:hover {
  background-color: rgba(79, 172, 254, 0.7);
  transform: translateY(-3px);
  box-shadow: 0 7px 15px rgba(79, 172, 254, 0.3);
}

.profile-section {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 4rem 2rem;
  background-color: rgba(15, 15, 20, 0.7);
  position: relative;
  z-index: 2;
}

@media (min-width: 768px) {
  .profile-section {
    flex-direction: row;
    justify-content: center;
    gap: 3rem;
  }
}

.profile-image {
  margin-bottom: 2rem;
}

@media (min-width: 768px) {
  .profile-image {
    margin-bottom: 0;
  }
}

.profile-image img {
  border-radius: 50%;
  width: 180px;
  height: 180px;
  object-fit: cover;
  border: 3px solid #4facfe;
  box-shadow: 0 0 20px rgba(79, 172, 254, 0.5);
  transition: transform 0.5s ease, box-shadow 0.5s ease;
}

.profile-image img:hover {
  transform: scale(1.05) rotate(5deg);
  box-shadow: 0 0 30px rgba(79, 172, 254, 0.8);
}

.profile-info {
  max-width: 600px;
}

.profile-info h2 {
  font-size: 2.2rem;
  margin-bottom: 1.5rem;
  color: #4facfe;
  position: relative;
}

.profile-info h2::after {
  content: '';
  position: absolute;
  bottom: -10px;
  left: 0;
  width: 50px;
  height: 4px;
  background: linear-gradient(45deg, #4facfe 0%, #00f2fe 100%);
  border-radius: 2px;
}

.project-buttons {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.project-button {
  display: block;
  padding: 1.2rem 1.5rem;
  background-color: rgba(30, 30, 40, 0.7);
  border-radius: 10px;
  text-decoration: none;
  color: #eee;
  transition: all 0.3s ease;
  border-left: 4px solid #4facfe;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
}

.project-button:hover {
  transform: translateX(8px);
  background-color: rgba(79, 172, 254, 0.2);
  border-left: 4px solid #00f2fe;
}

.project-name {
  font-size: 1.25rem;
  margin-bottom: 0.5rem;
  font-weight: 600;
}

.project-desc {
  font-size: 0.9rem;
  color: #aaa;
}

.menu-section {
  padding: 4rem 2rem;
  background-color: rgba(10, 10, 10, 0.8);
  position: relative;
  z-index: 2;
}

.menu-section h2 {
  font-size: 2.2rem;
  margin-bottom: 2rem;
  color: #4facfe;
  text-align: center;
  position: relative;
  display: inline-block;
}

.menu-section h2::after {
  content: '';
  position: absolute;
  bottom: -10px;
  left: 0;
  width: 50px;
  height: 4px;
  background: linear-gradient(45deg, #4facfe 0%, #00f2fe 100%);
  border-radius: 2px;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  max-width: 1200px;
  margin: 0 auto;
}

.menu-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 2rem;
  background-color: rgba(30, 30, 40, 0.7);
  border-radius: 15px;
  text-decoration: none;
  color: #eee;
  transition: all 0.3s ease;
  text-align: center;
  position: relative;
  overflow: hidden;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
}

.menu-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(45deg, #4facfe, #00f2fe);
  opacity: 0;
  transition: opacity 0.3s ease;
  z-index: -1;
}

.menu-card:hover {
  transform: translateY(-10px);
  color: #fff;
  box-shadow: 0 15px 30px rgba(79, 172, 254, 0.3);
}

.menu-card:hover::before {
  opacity: 0.2;
}

.menu-card i {
  font-size: 3rem;
  margin-bottom: 1rem;
  color: #4facfe;
  transition: transform 0.3s ease;
}

.menu-card:hover i {
  transform: scale(1.2);
  color: #fff;
}

.menu-card span {
  font-size: 1.2rem;
  font-weight: 500;

/* Responsive adjustments */
@media (max-width: 768px) {
  .main-title {
    font-size: 2.5rem;
  }
  
  .hero-content {
    padding: 1.5rem;
  }
  
  .profile-image img {
    width: 150px;
    height: 150px;
  }
  
  .menu-section h2, .profile-info h2 {
    font-size: 1.8rem;
  }
}
</style>




