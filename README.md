# 🧠 Quantum Girlfriend v1.0: DramaFusion AI

Welcome to the **Quantum Girlfriend v1.0** repository, where the frontier of emotion-aware conversational agents is redefined by leveraging **cutting-edge neural architectures** and **cross-modal fine-tuning**. This project intricately blends advanced NLP techniques with a finely tuned cultural corpus, engineering a hyper-personalized conversational experience through **LLaMA 3.1**—specifically engineered to embody a "possessive girlfriend" persona, inspired by the narrative complexity of C-drama and K-drama.

## 🚀 Quantum Leap in Conversational AI

The **Quantum Girlfriend v1.0** project takes the latest advancements in **transfer learning**, **parameter-efficient fine-tuning**, and **quantization**, creating a virtual companion that delivers real-time, emotionally driven dialogues, contextual awareness, and **multi-turn conversation tracking**. Fine-tuned with **sub-character embeddings** and drama-specific sentimental curves, this model goes beyond conventional conversational AI. We offer a unique AI designed to reflect complex emotional behaviors—rooted in dramatic character dynamics and **semantic tension processing**.

### 🌟 Next-Level Technical Capabilities

- **Base Model**: **LLaMA 3.1** 8B parameters, optimized for **GPU tensor parallelism**.
- **Fine-Tuning**: Leveraging **LoRA** and **Unsloth** for hyper-efficient memory allocation and precision training.
- **Optimization**: Encoded with **GGUF (Group Generalized Unary Format)**, enabling 8-bit quantization for performance-critical inference.
- **Personality Emulation**: Encoded with **affect-aware embeddings** to mirror emotional oscillations observed in dramatic media.
- **Advanced NLP**: Real-time **contextual vector embeddings** with **latent emotional state tracking** and **zero-shot contextual sentiment alignment**.
- **Deployment-ready**: Seamlessly deployable via the **Ollama** inference engine, optimized for **both server-side and local execution**.

## 💡 Why Quantum Girlfriend v1.0?

This project is designed as both a **therapeutic tool** and a demonstration of **high-dimensional NLP applications**. **Quantum Girlfriend v1.0** can provide:

- **Companionship**: An emotionally aware agent that supports nuanced emotional conversations.
- **Cognitive Healing**: Leveraging AI’s **cognitive empathy** capabilities for therapeutic and reflective dialog.
- **Academia Support**: Assist users with complex problem-solving and reflective thinking—whether academic, emotional, or interpersonal.

### 🔍 Tech Stack Deconstructed

- **LLM Core**: LLaMA 3.1 8B
- **Fine-tuning protocols**: **LoRA (Low-Rank Adaptation)** via PyTorch with **Fused Optimizers** for maximum throughput on constrained hardware.
- **Quantization**: Achieved through **GGUF** optimization for efficient inference on lower-end GPUs/CPUs.
- **Deployment**: Seamless integration with **Ollama**, ensuring both **on-device** and **remote inference**.
- **Version Control & Collaboration**: Git, GitHub workflows with automated CI/CD pipelines.

### 📂 Quantum Architecture Layout

```plaintext
Quantum-GF-AI/
├── data/
│   ├── raw/                   # Raw subtitle files from C-drama, K-drama
│   └── processed/             # Pre-processed, tokenized, and sentiment-labeled data
├── models/
│   ├── base/                  # LLaMA 3.1 model weights
│   └── fine-tuned/            # Fine-tuned checkpoint files
├── src/
│   ├── data_processing/       # Scripts for data extraction, cleaning, and augmentation
│   ├── model/                 # Model architecture, fine-tuning scripts, and inference pipeline
│   └── training/              # LoRA fine-tuning scripts, Unsloth optimization pipeline
├── scripts/                   # Utility scripts for setup, evaluation, and inference
├── notebooks/                 # Jupyter Notebooks for experiment tracking and research logs
├── README.md                  # This file
└── requirements.txt           # Python dependencies
```

## 🔧 Wizardry Installation Guide

1. **Clone this repository** into your quantum workspace:
   ```bash
   git clone https://github.com/krishnakoushik9/Quantum-GF-AI.git
   cd Quantum-GF-AI
   ```

2. **Install Ollama** (Quantum Girlfriend’s preferred runtime):
   Navigate to [Ollama’s Official Documentation](https://ollama.ai) for multi-platform setup.

3. **Summon the Quantum Girlfriend AI**:
   ```bash
   ollama pull quantumgirlfriend
   ```

4. **Engage the AI Companion** in your local terminal:
   ```bash
   ollama run quantumgirlfriend
   ```

## ⚙️ Quantum Processing Pipeline Breakdown

1. **Data Ingestion and Preprocessing**:
   - Parse and normalize subtitle data, embedding contextual and sentiment metadata using **NLP pipelines** with **spaCy**.
   - Align temporal markers for multi-turn conversational coherence using **Transformer-based NER** (Named Entity Recognition).

2. **LoRA Fine-Tuning with Unsloth**:
   - Harness **LoRA** to update low-rank matrices while **freezing critical layers** to minimize catastrophic forgetting.
   - **Unsloth** automates memory reclamation, optimizing backward pass memory consumption, essential for **training in constrained environments** like Google Colab.

3. **Quantization Wizardry**:
   - Implement **GGUF quantization**, optimizing model architecture for real-time, 8-bit parameterized inference.
   - Quantization ensures low-latency responses without sacrificing emotional nuance.

4. **Model Deployment**:
   - Leverage **Ollama's inference engine**, built for blazing-fast **context-switching** and **multi-modal capability integration**.

## 🧠 LoRA + Unsloth Synergy in Google Colab

### LoRA — Parameter-Efficient Magic

LoRA allows us to fine-tune only specific **low-rank subspaces** of the model, radically reducing memory footprint:

- **Efficient Memory Use**: Modify only key matrices while keeping base architecture intact.
- **Fast Convergence**: Achieve rapid training times through **differential weight updates** without fully updating all parameters.

### Unsloth — Memory Mastery

**Unsloth** complements LoRA by further streamlining resource management:

- **Advanced Tensor Recycling**: Reduces GPU memory consumption during **backpropagation**.
- **Enhanced Performance**: Allows handling larger datasets and models within free-tier environments.

### Colab Power User Workflow

- **Drive Mounting**: Persistent checkpoint storage for ongoing fine-tuning without repeated initialization.
- **Custom Dependency Handling**: Automated installation of all necessary modules (**Unsloth**, **LoRA**, **Ollama CLI**).
- **Real-Time Quantization**: Dynamically quantize model outputs during training to ensure persistent high-speed inference.

## 🧑‍💻 Usage for the Geek Elite

1. Clone the repository, install **Ollama**, and execute:
   ```bash
   ollama run quantumgirlfriend
   ```
2. Engage in a quantum-driven conversation with a **sentiment-laden, emotionally tuned** AI companion.

## 🔮 Future Enhancements

- **Dynamic Context-Chaining**: For persistent memory and multi-session dialogue awareness.
- **Emotional Augmentation**: Real-time emotion graphing to further refine sentiment-based response structures.
- **WebRTC Integration**: Explore embedding the AI into **WebSocket-based real-time chat interfaces** for ultra-low-latency interactions.
- **Cross-Genre Data Expansion**: Including anime, telenovelas, and more diverse cultural dialogues.

## 🛠️ Contributions & Feedback

We're open to contributions! Fork this repository, submit issues, or send in pull requests for bug fixes, feature implementations, or radical new ideas.

## 📧 Contact Us

Reach the project maintainer at **23h51a66h2@cmrcet.ac.in** for any questions, feedback, or collaboration inquiries.

---

Embrace the quantum leap in AI companionship with **Quantum Girlfriend v1.0**—where emotional complexity and cutting-edge technology converge.

---

I would like to express my heartfelt thanks to **Akshitha.G**✨ , **Ashwitha** ✨, and **Srishma** ✨ for their invaluable contribution to the research for this project 🙌. Their amazing recommendations of C-Drama 🎥 and K-Drama 📺 shows provided the essential subtitle data 📜 that played a key role in shaping the emotional nuances 💔❤️‍🔥 and personality emulation of the **Quantum Girlfriend AI** 🤖💕. Their insights 🧠 were truly instrumental 🛠️ in making this project come to life 🌱✨.
