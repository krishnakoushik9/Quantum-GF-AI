# 🧠 Quantum Girlfriend v1.0: DramaFusion AI

![Version](https://img.shields.io/badge/version-1.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
[![GitHub issues](https://img.shields.io/github/issues/krishnakoushik9/Quantum-GF-AI)](https://github.com/krishnakoushik9/Quantum-GF-AI/issues)

Welcome to the **Quantum Girlfriend v1.0** repository, where the frontier of emotion-aware conversational agents is redefined by leveraging **cutting-edge neural architectures** and **cross-modal fine-tuning**.

## Table of Contents
- [🚀 Overview](#-overview)
- [💡 Why Quantum Girlfriend v1.0?](#-why-quantum-girlfriend-v10)
- [🔍 Tech Stack](#-tech-stack)
- [📂 Project Structure](#-project-structure)
- [🔧 Quick Start](#-quick-start)
- [⚙️ Technical Pipeline](#️-technical-pipeline)
- [🧠 Colab Integration](#-colab-integration)
- [🔮 Future Enhancements](#-future-enhancements)
- [🤝 Contributing](#-contributing)
- [📧 Contact](#-contact)
- [📄 License](#-license)

## 🚀 Overview

Quantum Girlfriend v1.0 is a hyper-personalized conversational AI that embodies a "possessive girlfriend" persona, inspired by the narrative complexity of C-drama and K-drama. It utilizes LLaMA 3.1 with advanced NLP techniques for emotionally driven dialogue.

This project intricately blends advanced NLP techniques with a finely tuned cultural corpus, engineering a hyper-personalized conversational experience through **LLaMA 3.1**—specifically engineered to embody a "possessive girlfriend" persona, inspired by the narrative complexity of C-drama and K-drama.

## 💡 Why Quantum Girlfriend v1.0?

This project serves as both a **therapeutic tool** and a demonstration of **high-dimensional NLP applications**. **Quantum Girlfriend v1.0** offers:

- **Companionship**: An emotionally attuned agent for deep, sentiment-aware conversation.
- **Cognitive Healing**: Using AI's **cognitive empathy** for therapeutic and reflective dialogue.
- **Support for Academia**: Help with complex problem-solving and reflective thought in academic, emotional, or interpersonal contexts.

## 🔍 Tech Stack

- **Base Model**: **LLaMA 3.1** with 8B parameters, optimized for **GPU tensor parallelism**.
- **Fine-Tuning**: Achieved through **LoRA** and **Unsloth** for hyper-efficient memory allocation and precision training.
- **Quantization**: Future release to support **GGUF (Group Generalized Unary Format)** for 4-bit quantization, enhancing performance on resource-limited devices.
- **Personality Emulation**: Encoded with **affect-aware embeddings** to simulate emotional dynamics, inspired by drama media.
- **Advanced NLP**: Real-time **contextual vector embeddings**, **latent emotional state tracking**, and **zero-shot contextual sentiment alignment**.
- **Deployment-ready**: Fully compatible with the **Ollama** inference engine, optimized for both **server-side and local execution**.

## 📂 Project Structure

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

## 🔧 Quick Start

1. **Clone the repository**:
   ```bash
   git clone https://github.com/krishnakoushik9/Quantum-GF-AI.git
   cd Quantum-GF-AI
   ```

2. **Install Ollama**: Follow the instructions on [Ollama's Documentation](https://ollama.ai).

3. **Run the AI**:
   ```bash
   ollama pull quantumgirlfriend
   ollama run quantumgirlfriend
   ```

## ⚙️ Technical Pipeline

1. **Data Preprocessing**:
   - Parse subtitles and embed contextual/sentiment metadata with **NLP pipelines** using **spaCy**.
   - Use **Transformer-based NER** for multi-turn conversation tracking and temporal alignment.

2. **LoRA Fine-Tuning with Unsloth**:
   - LoRA fine-tunes low-rank matrices while freezing core layers to prevent catastrophic forgetting.
   - **Unsloth** optimizes memory usage during backpropagation, crucial for **Google Colab** and constrained environments.

3. **Quantization**:
   - (Upcoming) **GGUF quantization** will enable 8-bit parameter optimization, ensuring **low-latency inference** on resource-constrained hardware.

4. **Deployment**:
   - Use **Ollama** for efficient inference, leveraging GPU tensor parallelism and dynamic context switching for real-time emotional dialogue.

## 🧠 Colab Integration

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

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature-branch-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-branch-name`
5. Submit a pull request

For major changes, please open an issue first to discuss what you would like to change.

## 📧 Contact

For questions, feedback, or collaboration, reach the project maintainer at **23h51a66h2@cmrcet.ac.in**.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Thank you to **Akshitha.G** for indispensable contributions in recommending C-Drama and K-Drama shows, which provided vital subtitle data for emotional and personality modeling in **Quantum Girlfriend AI**.

Made with ❤️ by Krishna Koushik
