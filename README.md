# Various-AI-projects
<h1>🚀 Logic Programming, ASP, Expert Systems, and Cognitive Agents</h1>

<p>
This repository contains a collection of projects in <strong>Logic Programming, Answer Set Programming (ASP), Expert Systems, and Cognitive Agents</strong>.
Each project explores different paradigms and tools, implementing intelligent reasoning and problem-solving strategies. 
Accompanying research reports are available in the respective directories.
</p>

<hr>

<h2>📄 Overview of the Projects</h2>

<ul>
  <li><strong>Solving Multi-Exit Mazes with Prolog</strong> – Implementing the <strong>A* algorithm</strong> in Prolog for solving complex mazes.</li>
  <li><strong>Expert System for Real Estate Recommendations</strong> – A rule-based system in <strong>CLIPS</strong> for property selection.</li>
  <li><strong>Escape Room Agent with Soar</strong> – A cognitive agent that learns to escape a locked room using <strong>reinforcement learning</strong>.</li>
  <li><strong>Sports Scheduling Optimization with Clingo</strong> – An ASP-based solution for optimizing <strong>league scheduling</strong>.</li>
</ul>

<hr>

<h2>🚀 Project Details</h2>

<h3>🧩 Solving Multi-Exit Mazes with Prolog</h3>
<p>
This project implements a <strong>Prolog-based solver</strong> for multi-exit mazes using the <strong>A* algorithm</strong>. The key aspects include:
</p>
<ul>
  <li><strong>Maze Generation:</strong> Randomized wall placement with controlled density.</li>
  <li><strong>Search Algorithm:</strong> Implementation of <strong>A*</strong> with Manhattan and Euclidean heuristics.</li>
  <li><strong>Performance Analysis:</strong> Execution times and memory usage on mazes up to <strong>1000x1000</strong>.</li>
  <li><strong>Comparison with IDA*:</strong> Evaluating node expansion and memory constraints.</li>
</ul>

<p><strong>📄 Report available in:</strong> <code>PrologMazeSolver/Report.pdf</code></p>

<hr>

<h3>🏡 Expert System for Real Estate Recommendations (CLIPS)</h3>
<p>
This project implements a rule-based <strong>expert system</strong> for recommending real estate properties. The system:
</p>
<ul>
  <li><strong>Captures user preferences</strong> for budget, location, and features.</li>
  <li><strong>Profiles the client</strong> based on age, family, and transportation needs.</li>
  <li><strong>Calculates a Certainty Factor (CF)</strong> to rank property recommendations.</li>
  <li><strong>Handles constraints</strong> (soft and hard filters) dynamically.</li>
</ul>

<p><strong>📄 Report available in:</strong> <code>RealEstateExpertSystem/Report.pdf</code></p>

<hr>

<h3>🤖 Escape Room Agent with Soar</h3>
<p>
This project implements a <strong>Soar-based cognitive agent</strong> that learns to escape a locked room. Key features include:
</p>
<ul>
  <li><strong>Agent Abilities:</strong> Observing, moving, picking up objects, and combining items.</li>
  <li><strong>Reinforcement Learning:</strong> Learning from rewards and penalties for actions.</li>
  <li><strong>Strategy Optimization:</strong> Experimenting with <strong>Q-Learning vs. SARSA</strong> for action selection.</li>
  <li><strong>Escape Strategy:</strong> Using objects creatively to reach and break a window.</li>
</ul>

<p><strong>📄 Report available in:</strong> <code>SoarEscapeRoom/Report.pdf</code></p>

<hr>

<h3>⚽ Sports Scheduling Optimization with Clingo (ASP)</h3>
<p>
This project applies <strong>Answer Set Programming (ASP)</strong> using <strong>Clingo</strong> to generate an optimized sports league schedule. Constraints include:
</p>
<ul>
  <li><strong>Home/Away Balance:</strong> Ensuring fair home and away games.</li>
  <li><strong>City Constraints:</strong> Preventing teams from the same city from playing at home on the same day.</li>
  <li><strong>Derby Management:</strong> Regulating matches between teams from the same city.</li>
  <li><strong>Performance Optimization:</strong> Parallel computation for solving large instances.</li>
</ul>

<p><strong>📄 Report available in:</strong> <code>SportsScheduling/Report.pdf</code></p>

<hr>

<h2>📈 Results and Analysis</h2>
<ul>
  <li><strong>Prolog Maze Solver:</strong> Efficiently solves large mazes with <strong>A*</strong>, showing significant speed-ups over IDA*.</li>
  <li><strong>Real Estate Expert System:</strong> Provides tailored property recommendations with an average success rate of <strong>85%</strong>.</li>
  <li><strong>Escape Room Agent:</strong> Learns optimal strategies to escape the room within <strong>10 learning iterations</strong>.</li>
  <li><strong>Sports Scheduling:</strong> Finds feasible schedules under complex constraints, optimizing league fairness.</li>
</ul>

<hr>

<p>🔥 <em>This repository explores multiple paradigms of logic-based AI, providing practical implementations of Prolog, CLIPS, Soar, and Clingo. 
Feel free to explore, test, and contribute! 🚀</em></p>

<br>
(It is possible that the reports in English contain words or formulas that are difficult to read due to automatic stranslation of the pdf; to read them correctly, consult the Italian version)
