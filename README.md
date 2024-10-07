# 🧠 Quantum Girlfriend v1.0: DramaFusion AI

Welcome to the **Quantum Girlfriend v1.0** repository, where the frontier of emotion-aware conversational agents is redefined by leveraging **cutting-edge neural architectures** and **cross-modal fine-tuning**. This project intricately blends advanced NLP techniques with a finely tuned cultural corpus, engineering a hyper-personalized conversational experience through **LLaMA 3.1**—specifically engineered to embody a "possessive girlfriend" persona, inspired by the narrative complexity of C-drama and K-drama.

## 🚀 Quantum Leap in Conversational AI

The **Quantum Girlfriend v1.0** project utilizes the latest in **transfer learning**, **parameter-efficient fine-tuning**, and **quantization**, creating a virtual companion capable of real-time, emotionally driven dialogue, with **contextual awareness** and **multi-turn conversation tracking**. Fine-tuned with **sub-character embeddings** and **drama-specific sentiment mapping**, this model exceeds conventional conversational AI by reflecting nuanced emotional behaviors rooted in dramatic character arcs and **semantic tension processing**.

### 🌟 Next-Level Technical Capabilities

- **Base Model**: **LLaMA 3.1** with 8B parameters, optimized for **GPU tensor parallelism**.
- **Fine-Tuning**: Achieved through **LoRA** and **Unsloth** for hyper-efficient memory allocation and precision training.
- **Quantization**: Future release to support **GGUF (Group Generalized Unary Format)** for 4-bit quantization, enhancing performance on resource-limited devices.
  > **Note**: The GGUF-encoded version is under development and will be released soon—stay tuned!
- **Personality Emulation**: Encoded with **affect-aware embeddings** to simulate emotional dynamics, inspired by drama media.
- **Advanced NLP**: Real-time **contextual vector embeddings**, **latent emotional state tracking**, and **zero-shot contextual sentiment alignment**.
- **Deployment-ready**: Fully compatible with the **Ollama** inference engine, optimized for both **server-side and local execution**.

## 💡 Why Quantum Girlfriend v1.0?

This project serves as both a **therapeutic tool** and a demonstration of **high-dimensional NLP applications**. **Quantum Girlfriend v1.0** offers:

- **Companionship**: An emotionally attuned agent for deep, sentiment-aware conversation.
- **Cognitive Healing**: Using AI’s **cognitive empathy** for therapeutic and reflective dialogue.
- **Support for Academia**: Help with complex problem-solving and reflective thought in academic, emotional, or interpersonal contexts.

### 🔍 Tech Stack Breakdown

- **LLM Core**: LLaMA 3.1 (8B parameters).
- **Fine-Tuning**: **LoRA (Low-Rank Adaptation)** with **Fused Optimizers** via PyTorch for efficient hardware utilization.
- **Quantization**: GGUF optimization for streamlined inference on CPUs and lower-end GPUs (upcoming).
- **Deployment**: Through **Ollama**, enabling **real-time inference** and **context switching**.
- **Version Control & Automation**: Managed with GitHub, incorporating automated CI/CD pipelines for seamless collaboration and version control.

## 📂 Quantum Architecture Layout

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

## 🔧 Installation Guide

1. **Clone the repository**:
   ```bash
   git clone https://github.com/krishnakoushik9/Quantum-GF-AI.git
   cd Quantum-GF-AI
   ```

2. **Install Ollama**: Follow the instructions on [Ollama’s Documentation](https://ollama.ai) for installation on various platforms.

3. **Run the AI**:
   ```bash
   ollama pull quantumgirlfriend
   ollama run quantumgirlfriend
   ```

## ⚙️ Technical Pipeline

### 1. **Data Preprocessing**:
   - Parse subtitles and embed contextual/sentiment metadata with **NLP pipelines** using **spaCy**.
   - Use **Transformer-based NER** for multi-turn conversation tracking and temporal alignment.

### 2. **LoRA Fine-Tuning with Unsloth**:
   - LoRA fine-tunes low-rank matrices while freezing core layers to prevent catastrophic forgetting.
   - **Unsloth** optimizes memory usage during backpropagation, crucial for **Google Colab** and constrained environments.

### 3. **Quantization**:
   - (Upcoming) **GGUF quantization** will enable 8-bit parameter optimization, ensuring **low-latency inference** on resource-constrained hardware.

### 4. **Deployment**:
   - Use **Ollama** for efficient inference, leveraging GPU tensor parallelism and dynamic context switching for real-time emotional dialogue.

## 🧠 Colab Integration for LoRA & Unsloth

### LoRA — Efficient Fine-Tuning

- **Low Memory Footprint**: LoRA allows fine-tuning of specific subspaces, maintaining efficiency.
- **Fast Convergence**: Differential updates lead to quicker model convergence without needing full parameter updates.

### Unsloth — Memory Optimization

- **Tensor Recycling**: Saves GPU memory by reclaiming resources during backpropagation.
- **Enhanced Performance**: Suitable for larger datasets in free-tier environments like **Google Colab**.

### Colab User Workflow

- **Mount Drive** for persistent storage and seamless checkpoint continuation.
- **Automated Dependency Installation**: Handles packages such as **Unsloth**, **LoRA**, and **Ollama**.
- **On-the-Fly Quantization**: Future support for quantizing models during training for enhanced inference speed.

## 🔮 Future Enhancements

- **Context-Chaining**: For persistent memory across multi-session dialogues.
- **Emotion Augmentation**: Real-time emotion graphs to refine sentiment-based responses.
- **WebRTC Integration**: Embedding AI into **WebSocket**-based chat interfaces for ultra-low-latency interactions.
- **Expanded Data Sources**: Broader coverage of emotional data from genres like anime and telenovelas.

## 🛠️ Contributions & Feedback

We're open to contributions! Fork the repository, submit issues, or send in pull requests for bug fixes, feature requests, or creative innovations.

## 📧 Contact Us

For questions, feedback, or collaboration, reach the project maintainer at **23h51a66h2@cmrcet.ac.in**.

---

Thank you to **Akshitha.G** and my sister **Harsha** for their indispensable contributions in recommending C-Drama and K-Drama shows, which provided vital subtitle data for emotional and personality modeling in **Quantum Girlfriend AI**.
