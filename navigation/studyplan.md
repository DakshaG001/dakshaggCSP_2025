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

  <h2 id="create-performance-task-cpt">🧪 Create Performance Task (CPT)</h2>

  <div class="study-card">
    <h3 id="general-requirements">General Requirements</h3>
    <ul>
      <li>Minimum of 9 hours of class time allocated.</li>
      <li>Students may collaborate on program development but must complete the video and Personalized Project Reference individually.</li>
    </ul>
  </div>

  <div class="study-card">
    <h3 id="submission-components">Submission Components</h3>
    <ol>
      <li>
        <strong>Program Code</strong>:
        <ul>
          <li>PDF file containing all program code with comments.</li>
          <li>Must include:
            <ul>
              <li>Instructions for input (user, device, online data stream, or file).</li>
              <li>Use of at least one list (or other collection type) to manage program complexity.</li>
              <li>At least one student-developed procedure with:
                <ul>
                  <li>Procedure name.</li>
                  <li>Return type (if necessary).</li>
                  <li>One or more parameters.</li>
                </ul>
              </li>
              <li>An algorithm within the procedure that includes sequencing, selection, and iteration.</li>
              <li>Calls to the student-developed procedure.</li>
              <li>Instructions for output based on input and program functionality.</li>
            </ul>
          </li>
        </ul>
      </li>
      <li>
        <strong>Video</strong>:
        <ul>
          <li>Demonstrates the running of the program and its functionality.</li>
          <li>Created independently by the student.</li>
        </ul>
      </li>
      <li>
        <strong>Personalized Project Reference</strong>:
        <ul>
          <li>Includes code segments and written responses.</li>
          <li>Completed individually without collaboration.</li>
        </ul>
      </li>
    </ol>
  </div>
</div>

