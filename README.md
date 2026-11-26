# Hi, I'm Raunak 👋

I'm a final-year **AI & ML engineering student** at M. S. Ramaiah Institute of Technology, Bengaluru.

I'm inquisitive by nature. I read a lot, on whatever topic catches my interest, and I learn best by building: most of what I know came from shipping real projects, hitting real constraints, and working out why things broke. I'd rather take the time to understand a problem properly than rush to a fix. For me, solving the problem *is* the fun part. I'm also a big believer in repetition: whatever you repeat, mentally or physically, gets stronger.

Lately that has meant **LLM agents**: making them genuinely useful, keeping them honest, and measuring whether they actually work. I also enjoy the less glamorous half: the backend, the tests and the pipeline that get it running for real users.

Away from the screen, I've been an active person since I was a kid. Sport is a big part of my life: I play **football** and **badminton** and do **athletics**. So are people: good conversations and close relationships matter a lot to me. And lately I've fallen deep into **coffee** culture, trying out brewing methods, beans and every kind of coffee I can find. I could probably make it as a chatty barista. ☕

---

## What I build

- 🤖 **AI agents and LLM apps**: tool-calling agents, structured outputs, embeddings and semantic search, LLM evals
- 🌐 **Full-stack apps**: React frontends with FastAPI or Node.js backends, SQL databases, REST APIs
- 🧠 **Machine learning**: from feature engineering and model training to explainability and deployment
- 🚀 **Shipping it**: Docker, CI/CD with GitHub Actions, cloud deploys, monitoring

---

## Featured projects

### 🌱 [Groot: AI agents for college placements](https://github.com/raunakkukreja/groot) &nbsp;[`Live demo`](https://groot-agents.onrender.com)
Three AI agents that work together: one reads college email and keeps your calendar, one tailors your resume to each placement drive **without inventing anything**, and one plans your prep until the interview.
- Tool-calling chat agent, and search by meaning with embeddings (finds the right drive first in **90%** of test searches vs 70% for keyword search)
- An LLM eval harness on 31 labeled emails; it found a prompt problem whose fix took a local model's date accuracy from **59% to 82%**
- Code-level guardrails against invented data and prompt injection; Docker + GitHub Actions CI/CD, deployed only after tests pass

`Python` `FastAPI` `LiteLLM` `Gemini` `Ollama` `Embeddings` `SQLite` `React` `Docker` `GitHub Actions`

---

### 🏥 [PCOSense: PCOS risk screening](https://github.com/raunakkukreja/pcos_model) &nbsp;[`Live`](https://pcosense-app.vercel.app/)
An explainable AI health tool that combines a **ResNet-18 CNN** (ultrasound images) with an **XGBoost** classifier (symptom survey), and explains every result with SHAP and Grad-CAM.
Backend split into Dockerized services on Google Cloud Run and Render, cutting deployment time from 20 to 2 minutes.

`Python` `PyTorch` `XGBoost` `SHAP` `FastAPI` `React` `Docker` `GCP`

---

### 🎮 [Living Worlds: AI-powered NPC game engine](https://github.com/raunakkukreja/AI_NPCs) &nbsp;[`Live`](https://ai-npcs.vercel.app) &nbsp;`Top 120 of 900+ teams, Samsung PRISM Hackathon 2025`
A 2D RPG where 11 NPCs are driven by a locally hosted, quantized **LLaMA 3 8B** model, with no cloud API.
A custom gossip and memory system lets NPCs remember conversations, share information and form opinions about each other; replies stream token by token over Server-Sent Events.

`Python` `FastAPI` `llama-cpp-python` `Node.js` `React` `Canvas API`

---

### ✋ [Air Canvas 3D: draw in the air](https://github.com/raunakkukreja/Air-Canvas) &nbsp;[`Live`](https://air-canvas-3d.vercel.app)
Paint with hand gestures, in 2D and 3D, right in the browser. Hand tracking runs on-device with MediaPipe, so no video ever leaves your machine.
12 gestures with smoothing, 3D drawing from fingertip positions, and export to PNG, `.obj` and Three.js.

`JavaScript` `MediaPipe` `HTML5 Canvas` `Three.js` `Vercel`

---

### 🏏 [Fantasy Cricket ML Optimizer](https://github.com/raunakkukreja/virat_query) &nbsp;`Top 5%, FIFS Gameathon 2.0 (300+ teams)`
Predicts IPL players' fantasy points with an **XGBoost + LightGBM + neural network** ensemble, then picks the best team by solving a **0-1 knapsack** problem (PuLP) under budget and role rules.

`Python` `XGBoost` `LightGBM` `TensorFlow` `PuLP` `pandas`

---

### More projects
- 🗺️ [AI-Augmented A* Pathfinding](https://github.com/raunakkukreja/Augmented-A-star): replaced A*'s fixed heuristic with a learned model, cutting node expansions by up to 60%.

---

## Tech stack

**Languages:** `Python` `JavaScript` `TypeScript` `SQL` `Java` `C/C++` `HTML/CSS`

**AI and LLMs:** `LLM agents` `Tool calling` `Structured outputs` `Embeddings` `Semantic search` `LLM evals` `LiteLLM` `Gemini API` `Ollama` `llama.cpp`

**Machine learning:** `PyTorch` `TensorFlow` `XGBoost` `LightGBM` `Scikit-Learn` `SHAP` `Grad-CAM` `MediaPipe`

**Backend and data:** `FastAPI` `Flask` `Node.js` `Express.js` `REST APIs` `Pydantic` `SSE` `PostgreSQL` `SQLite` `Supabase`

**Frontend:** `React` `Vite` `Canvas API` `Three.js`

**DevOps and tools:** `Docker` `GitHub Actions` `pytest` `Git` `Google Cloud Run` `Render` `Vercel`

---

## Let's talk

I'm open to **software engineering (full-stack and backend), SDE-1 and AI engineer** roles and internships.
If something I built interests you, I'd love to hear from you.

📧 [raunakukreja@gmail.com](mailto:raunakukreja@gmail.com) &nbsp;·&nbsp; 💼 [LinkedIn](https://linkedin.com/in/raunakkukreja99)
