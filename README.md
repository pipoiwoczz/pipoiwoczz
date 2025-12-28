# 👋 Hi, I’m Lê Ngọc Anh Khoa

<p align="center">
  <b>AI Engineer Intern | Computer Science Student @ HCMUS</b><br/>
  <i>Focused on GPU-accelerated ML systems, Reinforcement Learning, Computer Vision, NLP, and RAG.</i><br/>
  <i>Experienced in building models both with frameworks and from scratch (CUDA / C++).</i>
</p>

---

<p align="center">
  <a href="https://pipoiwoczz.vercel.app"><img src="https://img.shields.io/badge/Website-1DA1F2?style=for-the-badge&logo=githubpages&logoColor=white"/></a>
  <a href="mailto:lengocanhkhoa2919@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/anh-khoa-l%C3%AA-ng%E1%BB%8Dc-836595354/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/pipoiwoczz"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>


---

## 💼 Key Skills

### 🧠 Machine Learning & AI

* **Deep Learning:** PyTorch, TensorFlow, Keras
* **Computer Vision:** YOLO, OpenCV, CLIP
* **NLP & RAG:** Transformers, LangChain, FAISS
* **Reinforcement Learning:** PPO, Minimax, Gymnasium

### ⚙️ Systems & Performance

* **GPU Programming:** CUDA C++, custom kernel design
* Memory coalescing, shared memory, kernel fusion
* im2col + SGEMM, CUDA streams, profiling (`nvprof`)

### 🛠️ MLOps / Tools

* Docker, FastAPI, Gradio
* NumPy, Pandas, Tableau
* Python, C++

---

<p align="center">
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
</p>

---

## 🌟 Selected Projects

### 🔥 GPU-Accelerated Convolutional Autoencoder (CUDA)

**C++ / CUDA | Parallel Programming | NVIDIA GPU**

* Implemented a **convolutional autoencoder entirely from scratch in CUDA** (no PyTorch, no cuDNN, no cuBLAS)
* Progressive pipeline: **CPU baseline → naive GPU → memory-optimized → batch + streams**
* Wrote custom kernels for:

  * Conv2D (forward & backward)
  * ReLU, MaxPooling, Upsampling
  * im2col / col2im
  * Adam optimizer
  * **Custom SGEMM**
* Achieved **>10× speedup vs CPU**, reducing training time from **>5000s → ~80s/epoch**
* Applied kernel fusion, persistent GPU memory, CUDA streams, double buffering
* Verified **CPU–GPU numerical correctness** at every optimization phase
* Extracted **8,192-dim latent features** and trained an SVM classifier
  → **60–65% CIFAR-10 accuracy**
* Profiling-driven optimization using `nvprof`

🔗 **Demo:** [https://youtu.be/-NXP8WncaFI](https://youtu.be/-NXP8WncaFI)
📊 **Report:** Colab Notebook
⚙️ **Tech:** CUDA 11+, C++17, Tesla T4 / RTX

### 🧩 Conversation-Data-Explorer (LLM + RAG)

* Natural language → SQL analytics platform
* FastAPI backend + React frontend
* Multi-LLM support (OpenAI, Gemini)

### 🎮 Reinforcement Learning for Super Mario Bros

* PPO with GAE, entropy regularization
* CNN actor-critic
* Custom reward shaping & wrappers

### 🐦 Twitter Sentiment Analysis

* BiLSTM trained on **1.6M tweets**
* Balanced F1, ~80% accuracy
* Optimized preprocessing pipeline

### 👗 Multimodal Fashion Search

* CLIP embeddings + FAISS
* 50k+ images
* Sub-0.5s retrieval latency

---

## 📊 GitHub Activity

<p align="center"> 
<img src="https://img.shields.io/badge/Primary%20Languages-Python%20|%20C++-blue?style=for-the-badge"/> 
<img src="https://img.shields.io/badge/Focus-AI%20%7C%20GPU%20%7C%20ML%20Systems-success?style=for-the-badge"/> 
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=pipoiwoczz&theme=tokyonight" />
</p>

---

## 📫 Contact

* 🌐 Portfolio: [https://pipoiwoczz.vercel.app](https://pipoiwoczz.vercel.app)
* 📧 Email: [lengocanhkhoa2919@gmail.com](mailto:lengocanhkhoa2919@gmail.com)
* 💼 LinkedIn: [linkedin.com/in/anh-khoa-lê-ngọc](https://www.linkedin.com/in/anh-khoa-l%C3%AA-ng%E1%BB%8Dc-836595354/)

---

![Visitor Counter](https://visitor-badge.laobi.icu/badge?page_id=pipoiwoczz.pipoiwoczz)

---

