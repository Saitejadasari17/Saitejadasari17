Hi there, I'm Sai Teja Dasari 👋

LinkedIn
Email
Research Project

🚀 About Me

I am a Software Engineer & Systems Researcher specializing in the intersection of Distributed Systems, Deep Reinforcement Learning (DRL), and Cloud Infrastructure.

🎓 Department of Software Engineering, Delhi Technological University (DTU)
🔬 Author of "Adaptive Load Balancing in Distributed Systems Using a Dueling Double DQN with Prioritized Experience Replay"
⚙️ Passionate about designing low-latency routing algorithms, distributed scheduling, and high-throughput backend services.
🛠️ Daily stack: Python, PyTorch, FastAPI, Gymnasium, React, Docker, Linux, Git.
🌟 Featured Research & Engineering Project
⚡ Adaptive RL Load Balancer

A self-learning request router for cloud server clusters that adapts dynamically to non-stationary and bursty server workloads.

Core Algorithm: Dueling Double DQN with Prioritized Experience Replay (PER), Huber Loss, and Polyak soft target updates.
Novel Contribution: Introduced temporally-extended ("sticky") exploration bursts to solve exploration-induced policy collapse in symmetric multi-server environments.
Benchmark Evaluation: Evaluated against Round Robin, Least Connections, Random, and Weighted RR under real production traffic traces from the Microsoft Azure Functions (2019) Dataset.
Results: Achieved ~30–40% lower response latency than Round Robin and Jain's Fairness Index 
≥
0.999
≥0.999 across five independent seed runs.
Full Stack Deployment: Packaged with a high-throughput FastAPI backend and an interactive React + Vite + TailwindCSS monitoring dashboard.
 Tech Stack & Technical Competencies
Domain	Technologies & Frameworks
Languages	Python (3.10+), JavaScript / TypeScript, SQL
Machine Learning & RL	PyTorch, Gymnasium, Dueling Double DQN, Prioritized Experience Replay, TensorBoard, NumPy, Pandas
Distributed Systems & Backend	FastAPI, Uvicorn, RESTful APIs, Concurrency & Threading, Load Balancing Algorithms
Frontend & UI	React, Vite, Tailwind CSS, Recharts
DevOps & Cloud Tools	Git / GitHub Actions, Docker, Linux / Bash, Render, Vercel
💬 What Interviewers Love Discussing With Me

If you're interviewing me, here are some fun, deep technical topics I'm excited to dive into:

Why standard 
𝜖
ϵ-greedy exploration fails in multi-server distributed routing (and how sticky temporal exploration fixes state trajectory collapse).
Prioritized Experience Replay (PER): Overcoming sample inefficiency with SumTree data structures and importance-sampling bias correction (
𝛽
β-annealing).
Decoupling Action Selection vs. Evaluation: Why Double DQN prevents Q-value overestimation bias in high-variance network latency environments.
Jain's Fairness vs. Greedy Optimization: The trade-off between power-of-d-choices (Least Connections) and tail latency (
𝑃
99
P99) under skewed server capacities.
 GitHub Stats & Activity

 

GitHub Streak
