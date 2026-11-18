## Hi, I'm Gunjan 👋

**AI/ML Engineer · Reinforcement Learning · LLM Applications · Computer Vision**

I'm an MPhil researcher at **Queensland University of Technology (QUT)** in Brisbane. I work on deep reinforcement learning for sequential decision-making under partial observability. I also build full-stack AI tools with on-device LLMs, retrieval and computer vision.

- 🔬 **Thesis:** *Learning Under Partial Observability: LSTM-Augmented Proximal Policy Optimization for Variable Speed Limit Control*
- 💼 **Looking for:** AI/ML Engineer and ML Engineer roles in Australia
- 📫 **Reach me:** [LinkedIn](https://www.linkedin.com/in/g726s) · gunjan.shinde.work@gmail.com

---

### 🧠 Research

**Recurrent PPO for control under partial observability (MPhil, QUT)**
I framed variable speed limit control as a POMDP and built a recurrent PPO agent (LSTM, shared-backbone actor–critic) in TensorFlow/Keras, trained in an Aimsun traffic microsimulation.
- I tested the environment's Markov assumption with Chi-square, Chapman–Kolmogorov and forward–backward tests, and found evidence of non-Markovian behaviour.
- I diagnosed and fixed a reward-hacking failure in which the agent learned a passive "do-nothing" policy.
- Across 3 traffic demand profiles with 100 randomised scenarios each, adding sequence memory **reduced total travel time by 5–8% compared with standard PPO**.

---

### 🚀 Projects

| Project | What it is | Stack |
|---|---|---|
| [**Innerlooop**](https://github.com/neutr0nStar/innerlooop) | A privacy-first conversational journaling app (team project, AIML Hackathon 2026). The LLM runs fully on-device, and FAISS semantic memory recalls past sessions. | Gemma via Ollama, FAISS, LangChain, FastAPI, React, Electron |
| [**BrainQuest**](https://github.com/G726S/BrainQuest) | An AI study app (hackathon, Aug 2026). It turns course PDFs into grounded flashcards, quizzes and notes using schema-constrained generation and adaptive difficulty, then gamifies revision. | Gemini API, FastAPI, React 19, TypeScript, Phaser |
| [**SPRINT-imputations**](https://pypi.org/project/SPRINT-imputations/) | A Python library on PyPI for imputing spatiotemporal traffic data. I refactored and packaged it from a research codebase. | Python, NumPy, tensor decomposition |
| [**Smart Grader**](https://github.com/G726S/smart-grader) | An early NLP prototype (2023) that grades free-text answers against a model answer using semantic embeddings. | Cohere embeddings, Annoy, Streamlit |

**Earlier work:** As AI/ML Head at WictroniX AtlanZ, I built a custom YOLOv8 vehicle-detection model (87% F1) for drone-based traffic analytics.

---

### 📄 Publication

**[Prioritizing Local Temporal Context in Traffic Data Imputation by Tensor Decomposition](https://australasiantransportresearchforum.org.au/prioritizing-local-temporal-context-in-traffic-data-imputation-by-tensor-decomposition/)**
*Australasian Transport Research Forum (ATRF)*

---

### 🛠️ Toolbox

**ML / RL:** PyTorch · TensorFlow/Keras · scikit-learn · PPO · DQN · POMDPs
**LLMs:** Gemini API · Ollama/Gemma · FAISS · RAG · structured generation
**Vision:** YOLOv8 · segmentation · object tracking
**Engineering:** Python · TypeScript · C/C++ · SQL · FastAPI · React · Git
