# Hi, I'm Jake Takahashi 👋

**Computer Science & Engineering @ UC Merced**  
**Machine Learning • Computer Vision • AI Systems • Software Engineering**

I'm a final-year Computer Science & Engineering student at the **University of California, Merced**, graduating in **May 2027**.

I enjoy building systems that go beyond isolated demos: long-running AI simulations, reproducible ML infrastructure, computer vision prototypes, evaluation pipelines, and software with enough testing and structure to survive continued development.

A lot of my recent work has centered around a simple philosophy:

> **"Great things come from hard work and perseverance. No excuses."**  
> — Kobe Bryant

I like learning by building, iterating aggressively, measuring what works, and turning experiments into real systems.

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

The project has grown to **500+ automated tests** alongside dedicated evaluation suites for long-horizon behavior, planning, commitments, economics, social decisions, and other system invariants.

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
- Hyperparameter search
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

## 👣 UnderStep

**Computer vision research exploring the feet as a secondary input channel**

UnderStep investigated whether foot gestures could provide an additional human-computer interaction channel while a user's hands remain occupied with another task.

I worked on the system as an **Undergraduate Research Intern**.

### My work included

- Building synchronized RGB / infrared camera capture pipelines
- Developing image acquisition and preprocessing tools
- Experimenting with camera placement and hardware configurations
- Investigating differences between RGB and IR camera characteristics
- Implementing gesture-state logic
- Building experimental prototypes using Python and OpenCV
- Evaluating practical constraints of vision-based foot interaction

The project combined **computer vision, hardware experimentation, and HCI** rather than treating perception as a purely offline ML problem.

The work was presented through the UC Berkeley **CITRIS Workforce Innovation Program**.

**Tech:** Python • OpenCV • Computer Vision • RGB/IR Imaging • HCI • Hardware Prototyping

---

## 👁️ Computer Vision & ML Benchmarking

**UC Merced CSE 176**

My computer vision work includes building reproducible experiments across classical machine learning, learned image features, and image-processing techniques.

One major experimental pipeline compared representations