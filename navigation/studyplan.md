---
layout: page
title: Study Guides with links
permalink: /study/
---

<style>
/* Dark theme styling for study page */
body {
  background-color: #0a0a0a;
  color: #eee;
  font-family: 'Poppins', sans-serif;
}

.container {
  max-width: 1000px;
  margin: 0 auto;
  padding: 2rem;
  background-color: rgba(15, 15, 20, 0.7);
  border-radius: 15px;
  box-shadow: 0 0 30px rgba(0, 0, 0, 0.3);
}

h1, h2, h3, h4 {
  color: #4facfe;
  position: relative;
  margin-bottom: 30px; /* Increased space below headings */
}

h1::after, h2::after {
  content: '';
  position: absolute;
  bottom: -15px; /* Moved the underline further down */
  left: 0;
  width: 50px;
  height: 3px; /* Slightly thinner line */
  background: linear-gradient(45deg, #4facfe 0%, #00f2fe 100%);
  border-radius: 2px;
}

a {
  color: #4facfe;
  text-decoration: none;
  transition: all 0.3s ease;
}

a:hover {
  color: #00f2fe;
  text-decoration: underline;
}

ul {
  list-style-type: none;
  padding-left: 0;
}

li {
  margin-bottom: 1rem;
  padding-left: 1.5rem;
  position: relative;
}

li::before {
  content: '→';
  position: absolute;
  left: 0;
  color: #4facfe;
}

.study-card {
  background-color: rgba(30, 30, 40, 0.7);
  border-radius: 10px;
  padding: 1.5rem;
  margin-bottom: 1.5rem;
  border-left: 4px solid #4facfe;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
  transition: all 0.3s ease;
}

.study-card:hover {
  transform: translateX(5px);
  border-left: 4px solid #00f2fe;
  background-color: rgba(79, 172, 254, 0.1);
}

code {
  background-color: rgba(255, 255, 255, 0.1);
  padding: 0.2rem 0.4rem;
  border-radius: 4px;
  font-family: monospace;
}

strong {
  color: #4facfe;
}

hr {
  border: 0;
  height: 1px;
  background: linear-gradient(to right, transparent, rgba(255, 255, 255, 0.2), transparent);
  margin: 2rem 0;
}
</style>

<div class="container">
  <h1>Study Plan</h1>

  <div class="study-card">
    <ol>
      <li>Review Team Teach pages, create notes for them and a plan for review to put into flashcards (notes are below will organize better)</li>
      <li>Review Collegeboard Videos and practice key topics with flashcards</li>
      <li><a href="https://apcentral.collegeboard.org/media/pdf/ap-csp-student-task-directions.pdf">AP Computer Science Principles Student Handout</a> <- Review the student Handbook</li>
    </ol>
  </div>

  <h2>AP CSP Review Materials</h2>
  
  <div class="study-card">
    <ul>
      <li><a href="https://dakshag001.github.io/dakshaggCSP_2025/2025/04/04/first_IPYNB_2_.html">Computing Innovations</a></li>
      <li><a href="https://dakshag001.github.io/dakshaggCSP_2025/2025/04/04/second_IPYNB_2_.html">Digital Divide</a></li>
      <li><a href="https://dakshag001.github.io/dakshaggCSP_2025/2025/04/04/third_IPYNB_2_.html">Crowdsourcing in Computing</a></li>
      <li><a href="https://dakshag001.github.io/dakshaggCSP_2025/2025/04/04/fourth_IPYNB_2_.html">Legal and Ethical Team Teach</a></li>
      <li><a href="https://dakshag001.github.io/dakshaggCSP_2025/2025/04/04/fifth_IPYNB_2_.html">Python Lists and Filtering Algorithms</a></li>
      <li><a href="https://dakshag001.github.io/dakshaggCSP_2025/2025/04/04/sixth_IPYNB_2_.html">Random Algorithms & Simulations</a></li>
      <li><a href="https://dakshag001.github.io/dakshaggCSP_2025/2025/04/04/seventh_IPYNB_2_.html">Graphs & Heuristics</a></li>
      <li><a href="https://dakshag001.github.io/dakshaggCSP_2025/2025/04/04/eigth_IPYNB_2_.html">Logic Gates</a></li>
      <li><a href="https://dakshag001.github.io/dakshaggCSP_2025/2025/04/04/ninth_IPYNB_2_.html">Images & Encoding Study</a></li>
      <li><a href="https://dakshag001.github.io/dakshaggCSP_2025/2025/01/24/sprint5blog_IPYNB_2_.html">Sprint 5 Blog & Review</a></li>
    </ul>
  </div>

  <h1 id="ap-computer-science-principles-ap-csp-overview">📘 AP Computer Science Principles (AP CSP) Overview</h1>

  <h2 id="big-ideas">🧠 Big Ideas</h2>

  <div class="study-card">
    <h3 id="1-creative-development-crd">1. Creative Development (CRD)</h3>
    <ul>
      <li>Emphasizes collaboration in program development.</li>
      <li>Utilizes iterative processes: investigating, designing, prototyping, and testing.</li>
      <li>Focuses on program design and development.</li>
      <li><strong>Exam Weight</strong>: 10%–13%</li>
    </ul>
  </div>

  <div class="study-card">
    <h3 id="2-data-dat">2. Data (DAT)</h3>
    <ul>
      <li>Explores how computers handle and process data.</li>
      <li>Covers data compression and extracting information from data.</li>
      <li><strong>Exam Weight</strong>: 17%–22%</li>
    </ul>
  </div>

  <div class="study-card">
    <h3 id="3-algorithms-and-programming-aap">3. Algorithms and Programming (AAP)</h3>
    <ul>
      <li>Involves developing algorithms and using abstractions.</li>
      <li>Includes simulations and algorithmic efficiency.</li>
      <li><strong>Exam Weight</strong>: 30%–35%</li>
    </ul>
  </div>

  <div class="study-card">
    <h3 id="4-computer-systems-and-networks-csn">4. Computer Systems and Networks (CSN)</h3>
    <ul>
      <li>Studies how computer systems and networks operate.</li>
      <li>Topics include the Internet and parallel/distributed computing.</li>
      <li><strong>Exam Weight</strong>: 11%–15%</li>
    </ul>
  </div>

  <div class="study-card">
    <h3 id="5-impact-of-computing-ioc">5. Impact of Computing (IOC)</h3>
    <ul>
      <li>Examines the effects of computing on society, economy, and culture.</li>
      <li>Discusses the digital divide, computing bias, and safe computing practices.</li>
      <li><strong>Exam Weight</strong>: 21%–26%</li>
    </ul>
  </div>

  <hr>

  <h2>4.1-4.3: The Internet & Computing Models</h2>
  
  <div class="study-card">
    <h3>4.1: The Internet Fundamentals</h3>
    <ul>
      <li><strong>Computing Devices & Systems</strong>: A computing device is a physical artifact that can run a program (computers, tablets, servers, routers)</li>
      <li><strong>Computer Networks</strong>: Interconnected computing devices capable of sending/receiving data</li>
      <li><strong>Routing</strong>: Finding a path from sender to receiver through a sequence of connected devices</li>
      <li><strong>Bandwidth</strong>: Maximum data sent in fixed time (measured in bits per second)</li>
      <li><strong>Internet Protocols</strong>: Standardized, open (nonproprietary) communication rules</li>
      <li><strong>Scalability</strong>: The Internet was designed to change in size and scale to meet new demands</li>
    </ul>
  </div>
  
  <div class="study-card">
    <h3>4.2: Fault Tolerance</h3>
    <ul>
      <li><strong>Fault Tolerance</strong>: Enables a system to continue functioning despite failures in components</li>
      <li><strong>Redundancy</strong>: Including extra components to mitigate failure</li>
      <li><strong>Network Redundancy</strong>: Having multiple paths between connected devices</li>
      <li><strong>Routing Adaptability</strong>: If a path fails, data can be sent via different routes</li>
      <li><strong>Benefits</strong>: Continued operation during unexpected failures, ability to scale to more devices/users</li>
      <li><strong>Challenges</strong>: Requires additional resources to implement redundancy</li>
    </ul>
  </div>
  
  <div class="study-card">
    <h3>4.3: Computing Models & Efficiency</h3>
    <ul>
      <li><strong>Sequential Computing</strong>: Operations performed one at a time in order</li>
      <li><strong>Parallel Computing</strong>:
        <ul>
          <li>Program broken into smaller operations performed simultaneously</li>
          <li>Contains both parallel and sequential portions</li>
          <li>More scalable than sequential computing</li>
          <li>Limited by sequential portion (Amdahl's Law)</li>
        </ul>
      </li>
      <li><strong>Distributed Computing</strong>:
        <ul>
          <li>Uses multiple devices to run a program</li>
          <li>Solves problems too large for single computers</li>
          <li>Allows larger problems to be solved more quickly</li>
        </ul>
      </li>
      <li><strong>Efficiency Calculations</strong>:
        <ul>
          <li>Sequential: Total time = sum of all steps</li>
          <li>Parallel: Total time = sequential tasks + longest parallel task</li>
          <li>Speedup = (Sequential time) / (Parallel time)</li>
        </ul>
      </li>
    </ul>
  </div>

  <a href="https://dakshag001.github.io/dakshaggCSP_2025/study/" class="study-card">
    <h3 style="text-align: center;">📚 Access Full Study Guide</h3>
  </a>
</div>

