# 🧭 The 24 Week Ascent

A **24-week (6-month)** journey to build mastery in **Mathematics, DSA, System Design, AI/ML foundations, and DevOps/MLOps**.  
This repository serves as both a **study tracker** and a **portfolio** of implementations, notes, and projects.  

---

## 📅 Timeline

- **Duration:** 24 Weeks (6 Months)  
- **Commitment:** ~7 hours/week (~168 hours total)  
- **Approach:**  
  - 📖 **Read strategically**: not every book needs deep reading. Some are for depth, some for breadth.  
  - ✍️ **Do exercises when marked**: only certain books require problem-solving focus.  
  - 💻 **Code weekly**: every phase produces implementations or mini-projects.  
  - 📝 **Commit weekly logs**: reflect on what was learned and what was hard.  

---

## 📂 Repository Structure
---

## 📌 Weekly Roadmap & Reading Instructions

### **Phase 0 – Foundations (Weeks 1–2)**
**Goal:** Rebuild math intuition, especially proofs and logic.  
- 📖 *How to Prove It* (Velleman) — **Read carefully** ch. 1–4. Do exercises.  
- 📖 MIT *Mathematics for CS* — **Skim sections** you know, but **solve induction and logic problems**.  
- 📖 Calculus Refresh (Khan Academy/Stewart) — **Skim** only core rules (derivatives, integrals).  
- ✍️ Deliverable: `01_foundations/proof_notes.md` with solved problems + proof strategies.  

---

### **Phase 1 – Core Math + DSA (Weeks 3–8)**
**Goal:** Strengthen discrete math and sharpen DSA problem-solving.  
- 📖 *Concrete Mathematics* (Knuth et al.) — **Read thoroughly ch. 1–5**, do **at least 3 exercises per chapter**.  
- 📖 *Algorithm Design* (Kleinberg & Tardos) — **Read selectively** (greedy, divide & conquer, dynamic programming).  
- 📖 *Algorithm Design Manual* (Skiena) — **Skim Part I (theory)**, use Part II (catalog) when stuck.  
- 💻 Implement weekly: heap, DSU, binary search variants, KMP, Fenwick tree.  
- ✍️ Deliverable: `02_dsa/` repo with 25 solved problems and clean implementations.  

---

### **Phase 2 – Probability + Advanced Algorithms (Weeks 9–12)**
**Goal:** Develop probabilistic reasoning & advanced structures.  
- 📖 *Probability and Computing* (Mitzenmacher & Upfal) — **Read thoroughly ch. 1, 4, 5**, solve 1–2 exercises per section.  
- 📖 *Concrete Mathematics* ch. 6–8 — **Read thoroughly** (generating functions, asymptotics).  
- 💻 Implement: randomized treap or RB-tree, suffix array, max-flow.  
- ✍️ Deliverable: `03_prob_advanced_dsa/` with implementations + notes on Chernoff bounds.  

---

### **Phase 3 – System Design + Software Engineering (Weeks 13–16)**
**Goal:** Learn to think like an architect, not just a coder.  
- 📖 *Designing Data-Intensive Applications* (Kleppmann) — **Read thoroughly ch. 1–6** (storage, replication, consistency).  
- 📖 *System Design Interview* (Alex Xu) — **Skim** for patterns (don’t memorize).  
- 📖 *Refactoring* (Fowler) — **Read selectively** to understand code smells.  
- 💻 Build 2–3 systems: URL shortener, news feed, rate limiter.  
- ✍️ Deliverable: `04_system_design/` with ADRs + diagrams + mini-service repo.  

---

### **Phase 4 – AI/ML Math & Core Models (Weeks 17–20)**
**Goal:** Understand math under ML and implement core models from scratch.  
- 📖 Strang — *Linear Algebra and Learning from Data* — **Read carefully** for intuition (do examples).  
- 📖 Shalev-Shwartz & Ben-David — *Understanding ML* — **Read thoroughly only first 5 chapters** (linear classifiers, VC dimension).  
- 📖 Bishop — *Pattern Recognition & ML* — **Skim selectively** for probabilistic view.  
- 💻 Implement: Linear regression, Logistic regression, Softmax, MLP (NumPy only, no sklearn).  
- ✍️ Deliverable: `05_ml_math_models/` with from-scratch models + gradient derivations.  

---

### **Phase 5 – DevOps + Cloud + MLOps (Weeks 21–24)**
**Goal:** Learn to package, deploy, monitor, and operate systems.  
- 📖 *Docker Deep Dive* (Nigel Poulton) — **Read thoroughly** first 10 chapters.  
- 📖 *Kubernetes: Up & Running* — **Read carefully** on Pods, Deployments, Services. Skim advanced operators.  
- 📖 *Accelerate* — **Read thoroughly** (engineering culture + CI/CD).  
- 📖 Chip Huyen — *Designing ML Systems* — **Skim** for MLOps workflows.  
- 💻 Tasks:  
  - Dockerize ML model + Phoenix/Rails service.  
  - Deploy to Kubernetes (minikube/kind or managed).  
  - Add monitoring (Prometheus + Grafana).  
  - Use MLflow/W&B for tracking.  
- ✍️ Deliverable: `06_devops_mlops/` repo with end-to-end ML service + CI/CD.  

---

### **Capstone (Week 24)**
Pick ONE:  
- **Distributed System** — scalable URL shortener (cache + metrics).  
- **ML System** — full ML pipeline (train → deploy → monitor).  
- ✍️ Deliverable: `07_capstone/` with:  
  - Final project repo (clean README, ADRs, diagrams).  
  - Benchmarks + screenshots/video.  

---

## 📚 Reading Strategy Guide

| Book | Strategy |
|------|----------|
| **How to Prove It (Velleman)** | Read slowly, solve most exercises. Core proof training. |
| **Concrete Mathematics** | Deep read ch. 1–8, exercises mandatory. This is the math backbone. |
| **Algorithm Design (K&T)** | Read selectively for methods (greedy, DP, flow). Skip trivialities. |
| **Algorithm Design Manual (Skiena)** | Skim theory, use catalog as reference. |
| **Probability and Computing** | Focus on tail bounds, randomized algorithms. Do exercises. |
| **DDIA (Kleppmann)** | Read carefully. This is your system design bible. |
| **Refactoring (Fowler)** | Skim, but practice identifying smells in your own code. |
| **Linear Algebra (Strang)** | Read for intuition, do worked examples. |
| **Understanding ML** | Read carefully, exercises optional. |
| **PRML (Bishop)** | Skim only. Too heavy for this timeline. |
| **Docker Deep Dive** | Read thoroughly to build mental model of containers. |
| **Kubernetes: Up & Running** | Read thoroughly up to Deployments & Services. Skim beyond. |
| **Accelerate** | Read fully, short but powerful. |
| **Designing ML Systems (Chip Huyen)** | Skim for workflows & MLOps patterns. |

---

## ✅ GitHub Workflow

- **Branches**  
  - `main`: stable deliverables  
  - `dev`: weekly work  
  - `feature/week-xx-topic`: per-task branches  

- **Commits**
- - **Progress Tracking**  
Maintain `docs/weekly_log.md`:  
```md
## Week 05
- ✅ Read Concrete Mathematics Ch. 3
- ✅ Solved 3 DP problems
- ✅ Implemented Binary Indexed Tree
- 🚧 Started notes on generating functions
