# Custom Large Language Model (LLM) – ChatGPT Style

> 🚧 Work in Progress  
> A personal project exploring how Large Language Models (LLMs) like ChatGPT are built and trained.

## 🧠 Key Components

### ✅ Data Collection & Preprocessing
<!-- - Used **FineWeb** dataset principles for curating large-scale textual data -->
- Performed cleaning and normalization
- Planned for multilingual dataset support
- Used **Shakespear** dataset to train the model  

### 🧩 Tokenization
- Implemented a simple encoding , decoding on the dataset
- Explored **Byte Pair Encoding (BPE)** for vocabulary compression

### 🧱 Model Architecture
- Based on **GPT architecture (Decoder-only Transformer)**
- Explored self-attention, positional embeddings, and masked attention mechanisms

### 🧪 Training Pipeline (Learning in progress)
- Supervised Fine-Tuning (SFT) using synthetic prompt-response pairs
- Planned to learn **RLHF (Reinforcement Learning from Human Feedback)** for alignment
- Experimenting in both **TensorFlow** and **PyTorch**

### 🖥️ Inference
- Working on deploying a demo interface using a small GPT model (e.g., GPT2-small) via HuggingFace Transformers

## 🛠️ Tech Stack
- Python, PyTorch, TensorFlow, HuggingFace Transformers
- Jupyter Notebooks
- Tokenizers (BPEmb, tiktoken)
- Google Colab & Local GPU (for training)

## 📌 Goals
- Understand and replicate the key stages of LLM development
- Fine-tune models for downstream NLP tasks
- Build an interactive chatbot based on a fine-tuned LLM

---
