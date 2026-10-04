# Hi, I'm Jake Takahashi 👋

**Computer Science & Engineering @ UC Merced**  
**Machine Learning • Computer Vision • AI Systems • Software Engineering**

I'm a final-year Computer Science & Engineering student at the **University of California, Merced**, graduating in **May 2027**.

I enjoy building systems that go beyond isolated demos: long-running AI simulations, reproducible ML infrastructure, computer vision pipelines, evaluation frameworks, and software with enough testing and structure to survive continued development.

A lot of my recent work has centered around a simple philosophy:

> **"Great things come from hard work and perseverance. No excuses."**  
> — Kobe Bryant

I learn best by building, iterating aggressively, measuring what works, and turning experiments into real systems.

---

## 🚀 What I'm Interested In

- Machine Learning & AutoML
- Computer Vision
- LLM systems and evaluation
- AI agents and autonomous systems
- Simulation and emergent behavior
- Applied AI research
- Software architecture
- Reproducible experimentation
- High-performance / GPU computing
- Developer tooling and automation

---

# 🧠 Featured Projects

## 🏙️ LLM-Town

**Persistent multi-agent social and economic simulation**

LLM-Town is my largest ongoing AI systems project: a deterministic simulation environment in which autonomous residents live inside a persistent town while interacting through both structured systems and real LLM-generated dialogue.

The project explores what happens when language models operate inside an environment where actions have persistent consequences instead of existing as isolated chatbot interactions.

### Major systems include

- Persistent residents, locations, schedules, and world state
- Memory and relationship systems
- Goals and long-horizon plans
- Social commitments and accountability
- Commitment failure, repair, cancellation, and replacement
- Economic transactions
- Jobs, wages, procurement, production, and commerce
- Materials and provenance
- Crime, evidence, and justice systems
- Dynamic activities and opportunities
- Structured LLM dialogue and action interpretation
- Deterministic simulation paths
- Save/load and reproducible seeded execution
- Real-LLM and deterministic evaluators

The architecture intentionally separates **LLM-generated behavior from authoritative simulation state**, allowing language models to propose actions while deterministic systems decide what actually occurs.

The project has grown to **500+ automated tests** alongside dedicated evaluation suites for long-horizon behavior, planning, commitments, economics, social decisions, and system invariants.

**Tech:** Python • LLMs • Agent Systems • Simulation • pytest • Structured Evaluation • Git

---

## ⚙️ BenchForge

**Reproducible AutoML and model benchmarking platform**

BenchForge is a classical machine-learning benchmarking and AutoML system built around a question I kept encountering in ML work:

> Given a dataset and a set of candidate approaches, how do we compare them rigorously rather than simply train a few models and pick the highest score?

BenchForge provides structured experimentation across classification and regression workflows.

### Features

- Binary classification
- Multiclass classification
- Regression
- Automated model benchmarking
- Hyperparameter optimization
- Nested cross-validation
- Optuna integration
- Leakage-safe fold-local preprocessing
- Deterministic random seeds
- Experiment fingerprints
- Task-aware metrics
- Model failure isolation
- Persistent experiment artifacts
- JSON / CSV result generation
- CLI-driven workflows
- Reproducible model comparison

The broader goal is to make ML experimentation **repeatable, inspectable, and statistically defensible** rather than dependent on one lucky train/test split.

**Tech:** Python • scikit-learn • Optuna • pandas • NumPy • pytest • AutoML

---

## 🤖 AgentBench Local

**Local coding-agent experimentation and evaluation**

AgentBench Local is an ongoing project exploring how local language models can be used as autonomous coding agents over longer software-development sessions.

The project focuses on the engineering challenges that appear when an LLM is allowed to modify a real repository repeatedly rather than answer isolated coding questions.

### Areas of exploration

- Multi-session coding-agent workflows
- Long-running autonomous implementation
- Repository state management
- Agent task decomposition
- Automated verification
- Regression detection
- Failure recovery
- Prompt and context design
- Local inference
- Architectural drift
- Quality assurance between agent passes

I use the project to experiment with open-weight coding models and to compare local agentic development with hosted coding systems.

**Tech:** Python • Local LLMs • Qwen • Git • Agentic Coding • Automated Evaluation

---

## 🔬 LLM Hallucination & Retrieval Study

**19,000+ inference runs across open-weight language models**

I built an experimental pipeline to study how retrieval context affects hallucination behavior in instruction-tuned LLMs.

The experiment evaluated:

- **8 open-source instruction-tuned models**
- Models ranging roughly from **3B–14B parameters**
- **800 retrieval scenarios**
- Multiple trials per condition
- **19,000+ valid inference runs**

The system varied properties including the amount of retrieved context and the location of the relevant document.

Responses were automatically classified into categories such as:

- Correct
- Abstained
- Wrong-document answer
- Hallucinated answer

The work required building a reproducible GPU inference pipeline, experiment orchestration, response classification, data aggregation, and analysis infrastructure.

Some long-context configurations produced hallucination rates as high as **13.3%**.

**Tech:** Python • Hugging Face Transformers • PyTorch • CUDA • LLM Evaluation • pandas • GPU Computing

---

## 👁️ Computer Vision & ML Benchmarking

**UC Merced CSE 176**

My computer vision work includes building reproducible experiments across classical machine learning, learned image representations, and image-processing techniques.

### Selected work

- MNIST digit classification
- Logistic regression benchmarking
- Random forest experiments
- XGBoost classification
- PCA-based dimensionality reduction
- Learned feature pipelines
- Image gradients
- Harris corner detection
- Projective geometry
- Homographies
- Camera intrinsics and extrinsics
- Image preprocessing
- Evaluation and experiment reproducibility

One project compared several approaches to handwritten-digit classification, including a PCA pipeline reducing **784 pixel dimensions to 148 components** while retaining approximately **80% of the variance**, followed by XGBoost classification reaching roughly **94.4% accuracy**.

I have also worked with classical computer vision concepts including perspective projection, homogeneous coordinates, vanishing points, image derivatives, and feature detection.

**Tech:** Python • NumPy • OpenCV • scikit-learn • XGBoost • PCA • Computer Vision

---

# 💻 Software & AI Engineering

A major part of my recent development process involves working with coding agents while maintaining architectural and quality control myself.

I use systems such as:

- OpenAI Codex
- ChatGPT
- Gemini CLI
- Local open-weight models
- Qwen-based coding agents

Rather than treating AI-generated code as automatically correct, I focus heavily on:

- Automated tests
- Regression suites
- Deterministic evaluators
- Repository-level validation
- Explicit invariants
- Failure-case testing
- Architectural separation
- Reproducible builds
- Incremental implementation
- Code review between agent passes

I am particularly interested in how software engineering changes when one developer can coordinate multiple AI systems while retaining responsibility for architecture, verification, and product direction.

---

# 🧪 Research & Experimentation

I enjoy projects where the answer is not obvious before the experiment begins.

My general workflow is:

1. Define a concrete question.
2. Build the smallest reproducible system that can test it.
3. Instrument the system heavily.
4. Run enough experiments to expose failure cases.
5. Analyze the results.
6. Improve the architecture.
7. Repeat.

I am especially interested in research questions involving:

- LLM reliability
- Retrieval and hallucination
- Agent behavior
- Long-horizon planning
- Evaluation methodology
- Computer vision
- Automated machine learning
- Human-AI software development

---

# 🎓 Education

## University of California, Merced

**B.S. Computer Science & Engineering**  
Expected Graduation: **May 2027**

Relevant areas of study include:

- Computer Vision
- Machine Learning
- Data Structures & Algorithms
- C++
- Computer Architecture
- Digital Logic
- Physics
- Software Engineering
- Linear Algebra
- Probability & Statistics

---

# 👨‍🏫 Experience

## STEM Tutoring Center — UC Merced

I work with students in STEM courses and help explain technical concepts, debug misunderstandings, and break complex problems into manageable steps.

Tutoring has strengthened my ability to communicate technical ideas clearly—especially when the person I'm helping approaches a problem differently than I do.

That skill translates directly into software development, collaboration, documentation, and technical interviews.

---

# 🖥️ Computing & Experimentation

I regularly work across both local development environments and university high-performance computing resources.

### HPC environment

- NVIDIA RTX 6000 Ada
- ~48 GB GPU memory
- Dual AMD EPYC processors
- Hundreds of GB of system memory
- CUDA / PyTorch workloads

I use this environment for:

- LLM inference
- Model benchmarking
- Large experimental sweeps
- GPU-based ML workloads
- Computer vision
- Local language-model experimentation

---

# 🛠️ Technologies

### Languages

`Python` `C++` `C` `SQL`

### Machine Learning

`PyTorch` `scikit-learn` `XGBoost` `Optuna` `Hugging Face Transformers`

### Computer Vision

`OpenCV` `NumPy` `PCA` `Image Processing`

### AI Systems

`LLMs` `Agent Systems` `RAG Evaluation` `Local Inference` `Structured Evaluation`

### Data

`pandas` `NumPy` `Matplotlib`

### Engineering

`Git` `GitHub` `pytest` `CLI Development` `Linux` `Jupyter`

### Compute

`CUDA` `GPU Computing` `HPC` `RTX 6000 Ada`

---

# 📈 How I Like to Build

I care about getting something real working early.

Instead of spending weeks trying to design a perfect system on paper, I prefer to build a strong first version, test it, discover where the assumptions break, and improve the architecture from evidence.

That approach has led many of my projects through repeated cycles of:

**Build → Test → Break → Measure → Refactor → Expand**

The goal is not simply to generate more code.

The goal is to build systems that become **more reliable as they become more ambitious**.

---

# 🏀 Outside of Code

Basketball has been a major influence on the way I think about improvement.

I respect the mentality associated with Kobe Bryant's approach to his craft: repetition, preparation, attention to detail, and being willing to put in the work long after the initial excitement disappears.

That same mentality is something I try to bring into engineering.

> **"Great things come from hard work and perseverance. No excuses."**  
> — Kobe Bryant

---

# 📫 Connect

I'm currently interested in opportunities involving:

**Machine Learning • Computer Vision • AI Engineering • Applied Research • Software Engineering**

I'm especially interested in teams building systems where experimentation, engineering rigor, and real-world AI intersect.