---
layout: post
title: Trimester 2 Final Showcase
permalink: /tri2/
comments: true
---

<div class="header-container">
  <div class="header-content">
    <h1 class="main-title">Trimester 2 Final Showcase</h1>
    <p class="subtitle">A 12-week journey of software development and learning</p>
  </div>
</div>

<div class="score-card">
  <h2>College Board Scoring</h2>
  
  <div class="score-grid">
    <div class="score-item">
      <div class="score-header">
        <span class="score-points">4.5</span>
        <span class="score-title">5 Things Over 12 Weeks</span>
      </div>
      <ul class="score-list">
        <li><span class="highlight">Backend Leaderboard</span> Implementation (1.0)</li>
        <li><span class="highlight">Frontend Development</span> (Competition Interface, Leaderboard, Posts) (1.0)</li>
        <li><span class="highlight">Admin Panel</span> Development (1.0)</li>
        <li><span class="highlight">Burndown List</span> Creation (0.5)</li>
        <li><span class="highlight">UI/UX</span> Improvements (1.0)</li>
      </ul>
    </div>
    
    <div class="score-item">
      <div class="score-header">
        <span class="score-points">2.0</span>
        <span class="score-title">Full Stack Demo</span>
      </div>
      <ul class="score-list">
        <li><span class="highlight">Backend:</span> User data storage, Score calculation</li>
        <li><span class="highlight">Frontend:</span> Interactive UI, Real-time updates</li>
        <li><span class="highlight">N@TM:</span> Feedback (Video evidence included)</li>
      </ul>
    </div>
    
    <div class="score-item">
      <div class="score-header">
        <span class="score-points">1.0</span>
        <span class="score-title">Project Feature Blog</span>
      </div>
      <ul class="score-list">
        <li>Used <span class="highlight">CPT terminology</span> in documentation</li>
        <li>Detailed <span class="highlight">technical implementation</span></li>
        <li><span class="highlight">Algorithm showcase</span> (Score calculation)</li>
      </ul>
      <div class="score-link">
        <a href="https://dakshag001.github.io/dakshaggCSP_2025/2025/01/24/sprint5blog_IPYNB_2_.html" class="button">
          <i class="fas fa-book"></i>
          View Project Feature Blog
        </a>
      </div>
    </div>
    
    <div class="score-item">
      <div class="score-header">
        <span class="score-points">1.0</span>
        <span class="score-title">MCQ Test</span>
      </div>
      <div class="score-link">
        <a href="https://dakshag001.github.io/dakshaggCSP_2025/2025/03/03/mcq2_IPYNB_2_.html" class="button">
          <i class="fas fa-clipboard-check"></i>
          View MCQ Corrections
        </a>
      </div>
    </div>
  </div>
  
  <div class="total-score">
    <span class="total-label">Total Score:</span>
    <span class="total-points">8.5 points</span>
  </div>
</div>

## 1. Backend Leaderboard Implementation

I designed the backend functionality for the leaderboard system, which includes:
- User data storage through a separate API
- Score calculation using mathematical functions
- Data persistence and retrieval

<div class="showcase-image">
    <img src="../images/notebooks/Screenshot 2025-03-02 142524.png" alt="Leaderboard Backend">
</div>


## 2. Frontend Development

### Competition Interface
- Designed interactive buttons
- Implemented word display system
- Created dynamic timer functionality

<div class="showcase-image">
    <img src="../images/notebooks/Screenshot 2025-03-02 142813.png" alt="Competition Interface">
</div>

### Leaderboard Display
- Developed dual input system:
  - Manual score entry
  - Automatic score calculation
- Real-time data visualization

<div class="showcase-image">
    <img src="../images/notebooks/Screenshot 2025-03-02 142916.png" alt="Leaderboard Frontend">
</div>

### Posts Layout
- Optimized image display system
- Implemented responsive box sizing

<div class="showcase-image">
    <img src="../images/notebooks/Screenshot 2025-03-02 143031.png" alt="Posts Frontend">
</div>

## 3. Admin Panel Development

Implemented CRUD functionality for administrative controls

<div class="showcase-grid">
    <div class="showcase-image">
        <img src="../images/notebooks/Screenshot 2025-03-01 131326.png" alt="Admin Panel 1">
    </div>
    <div class="showcase-image">
        <img src="../images/notebooks/Screenshot 2025-03-01 131303.png" alt="Admin Panel 2">
    </div>
</div>

## 4. Burndown List

Created detailed burndown lists for:
- Personal tasks
- Backend team tasks
- Team grading resolution

<div class="showcase-image">
    <img src="../images/notebooks/Screenshot 2025-03-01 131456.png" alt="Burndown Lists">
</div>

## 5. UI/UX Improvements

Enhanced the backend index page for improved team usability

<div class="showcase-image">
    <img src="../images/notebooks/Screenshot 2025-03-01 131243.png" alt="Index Page Styling">
</div>

## Bonus: N@TM Participation

Conducted peer reviews and interviews with other project groups

<div class="video-container">
    <iframe 
        width="100%" 
        height="315" 
        src="https://www.youtube.com/embed/ihp6rpVMqOI" 
        title="N@TM Interviews" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
    </iframe>
</div>

<style>
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

body {
  font-family: 'Poppins', sans-serif;
  background-color: #0a0a0a;
  color: #eee;
}

.container {
  background-color: transparent;
}

.header-container {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  padding: 3rem 2rem;
  margin-bottom: 2rem;
  border-radius: 15px;
  position: relative;
  overflow: hidden;
}

.header-container::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: url('https://images.unsplash.com/photo-1550439062-609e1531270e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
  background-size: cover;
  background-position: center;
  opacity: 0.15;
}

.header-content {
  position: relative;
  z-index: 2;
  text-align: center;
}

.main-title {
  font-size: 3rem;
  margin-bottom: 1rem;
  color: #fff;
  text-shadow: 0 2px 10px rgba(0,0,0,0.3);
}

.subtitle {
  font-size: 1.2rem;
  color: rgba(255,255,255,0.9);
}

h2 {
  font-size: 2rem;
  margin: 2rem 0 1.5rem;
  color: #4facfe;
  position: relative;
}

h3 {
  font-size: 1.5rem;
  margin: 1.5rem 0 1rem;
  color: #4facfe;
}

.score-card {
  background: rgba(30, 30, 40, 0.7);
  border-radius: 15px;
  padding: 2rem;
  margin-bottom: 2rem;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
}

.score-card h2 {
  text-align: center;
  margin-top: 0;
}

.score-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
}

.score-item {
  background: rgba(20, 20, 28, 0.5);
  border-radius: 10px;
  padding: 1.5rem;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
}

.score-header {
  display: flex;
  align-items: center;
  margin-bottom: 1rem;
}

.score-points {
  background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
  color: #fff;
  font-size: 1.2rem;
  font-weight: bold;
  width: 2.5rem;
  height: 2.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  margin-right: 1rem;
}

.score-title {
  font-weight: 600;
  font-size: 1.2rem;
}

.score-list {
  padding-left: 1.5rem;
}

.score-list li {
  margin-bottom: 0.5rem;
}

.highlight {
  color: #4facfe;
  font-weight: 500;
}

.total-score {
  display: flex;
  justify-content: flex-end;
  align-items: center;
  margin-top: 1.5rem;
  padding-top: 1rem;
  border-top: 1px solid rgba(255,255,255,0.1);
}

.total-label {
  font-size: 1.2rem;
  margin-right: 1rem;
}

.total-points {
  background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
  color: #fff;
  font-size: 1.2rem;
  font-weight: bold;
  padding: 0.5rem 1rem;
  border-radius: 25px;
}

.button {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
  color: white;
  padding: 0.75rem 1.5rem;
  border-radius: 25px;
  text-decoration: none;
  font-weight: 500;
  transition: all 0.3s ease;
  box-shadow: 0 4px 10px rgba(79, 172, 254, 0.3);
}

.button:hover {
  transform: translateY(-3px);
  box-shadow: 0 7px 15px rgba(79, 172, 254, 0.5);
}

.score-link {
  display: flex;
  justify-content: center;
  margin-top: 1rem;
}

.showcase-image {
  margin: 1.5rem 0;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
  transition: transform 0.3s ease;
}

.showcase-image:hover {
  transform: translateY(-5px);
}

.showcase-image img {
  width: 100%;
  height: auto;
  display: block;
}

.showcase-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin: 1.5rem 0;
}

.video-container {
  position: relative;
  padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
  height: 0;
  overflow: hidden;
  margin: 1.5rem 0;
  border-radius: 10px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
}

.video-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 0;
}

@media (max-width: 768px) {
  .main-title {
    font-size: 2.2rem;
  }
  
  .subtitle {
    font-size: 1rem;
  }
  
  h2 {
    font-size: 1.7rem;
  }
  
  h3 {
    font-size: 1.3rem;
  }
  
  .score-grid {
    grid-template-columns: 1fr;
  }
}
</style>