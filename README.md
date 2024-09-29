# 🔬 Quantum Girlfriend v1.0: DramaFusion AI

Welcome to the **Quantum Girlfriend v1.0** project repository! This innovative AI leverages advanced natural language processing (NLP) techniques to create a distinctive conversational experience by fine-tuning a large language model (LLM) with the personality traits of a "possessive girlfriend" inspired by popular C-dramas and K-dramas.

## 🚀 Project Overview

**Quantum Girlfriend v1.0** explores the fusion of large language models, personality emulation, and culturally specific dialogue patterns. Using the **Llama 3.1 8-billion-parameter model**, fine-tuned with curated data from Asian dramas, we aim to deliver an engaging AI companion with a deeply relatable and interactive persona.

### 🌟 Key Features

- **Model**: Fine-tuned **Llama 3.1** 8B parameters.
- **Training Dataset**: Subtitles from popular C-dramas and K-dramas.
- **Fine-tuning Framework**: **LoRA** and **Unsloth** for efficient model optimization.
- **Performance**: Quantized **GGUF** model for high-performance interaction.
- **Personality Emulation**: A possessive yet supportive companion, drawing traits from dramatic characters.
- **NLP Capabilities**: Advanced contextual understanding for emotionally nuanced conversations.
- **Deployment**: Easily run on local machines with **Ollama**.

### 💖 Project Purpose

The purpose behind **Quantum Girlfriend v1.0** is to provide emotional support and companionship while encouraging personal reflection and healing. It is designed to offer the following:

- **Companionship**: Offer solace and emotional support to individuals experiencing loneliness or heartbreak.
- **Healing**: Serve as an emotional aid, providing motivation for personal growth.
- **Academic Aid**: Assist in various tasks, such as study and problem-solving.

While this AI can offer comfort, it's also designed to foster self-reliance and mental resilience, encouraging users to explore healthy practices for overcoming emotional challenges.

## 🛠️ Technical Stack

- **Model**: Llama 3.1 8B
- **Fine-tuning**: LoRA (Low-Rank Adaptation) using PyTorch
- **Optimization**: Unsloth for memory-efficient training
- **Quantization**: GGUF format for performance optimization
- **Deployment**: Ollama platform for local and server-side interaction
- **Version Control**: Git, GitHub

## 📂 Project Structure

```
Quantum-GF-AI/
├── data/
│   ├── raw/
│   └── processed/
├── models/
│   ├── base/
│   └── fine-tuned/
├── src/
│   ├── data_processing/
│   ├── model/
│   └── training/
├── scripts/
├── notebooks/
├── README.md
└── requirements.txt
```

## 🔧 Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/krishnakoushik9/Quantum-GF-AI.git
   cd Quantum-GF-AI
   ```

2. Install **Ollama**:
   Follow the official instructions at [Ollama's website](https://ollama.ai) to install the platform for your OS.

3. Install the QuantumGirlfriend model:
   ```bash
   ollama pull quantumgirlfriend
   ```

4. Run the model:
   ```bash
   ollama run quantumgirlfriend
   ```

## 🎛️ Model Training Pipeline

1. **Data Collection and Preprocessing**:
   - Extract and clean subtitles from popular C-dramas and K-dramas.
   - Label dialogues with context and sentiment to enhance personality emulation.

2. **Fine-tuning with LoRA and Unsloth**:
   - Set up Google Colab (free tier) environment for cost-effective training.
   - Load the Llama 3.1 8B model and apply LoRA for efficient parameter fine-tuning.
   - Utilize Unsloth for optimization, making it possible to train larger models in memory-constrained environments.

3. **Quantization and Optimization**:
   - Quantize the fine-tuned model to **GGUF** for enhanced performance.
   - Optimize quantization parameters for smooth inference.

4. **Deployment**:
   - Package and publish the model for easy use with **Ollama**.
   - Deploy via `ollama pull` for effortless local use.

## 🧠 LoRA and Unsloth in Google Colab (Free Tier)

### Low-Rank Adaptation (LoRA)

LoRA allows us to fine-tune large models by focusing on a subset of the parameters:

- **Reduced Memory**: LoRA reduces memory usage by fine-tuning only low-rank matrices.
- **Efficiency**: Enables fast training and low-resource inference, perfect for hardware like Google Colab's free tier.

### Unsloth

**Unsloth** enhances LoRA's efficiency by speeding up training and reducing memory usage:

- **Speed**: Training is faster and more memory-efficient.
- **Optimized Inference**: Reduces memory consumption, allowing larger batch sizes and longer training times without crashing.

### Colab Workflow

- **Mount Google Drive**: Ensure persistent storage of model checkpoints.
- **Install Dependencies**: Install Unsloth and LoRA libraries.
- **Train and Quantize**: Train the model with LoRA, quantize it with Unsloth optimizations.
- **Save Checkpoints**: Store training progress on Google Drive for future use.

## 💻 Usage

To interact with **Quantum Girlfriend v1.0**:

1. Ensure **Ollama** is installed.
2. Run the model with:
   ```bash
   ollama run quantumgirlfriend
   ```
3. Enjoy interacting with the AI companion in your terminal!

## 🎯 Future Improvements

- **Multi-turn Conversations**: Implement context-tracking for sustained dialogue.
- **Advanced Emotion Detection**: Improve emotional intelligence of the AI.
- **Web Interface**: Build a user-friendly web-based chat interface.
- **Expand Dataset**: Incorporate more diverse data from various drama genres.

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues, suggest enhancements, or create pull requests.

## 📞 Contact

For any questions or feedback, please contact the project maintainer at **23h51a66h2@cmrcet.ac.in**.

---

We hope you enjoy interacting with **Quantum Girlfriend v1.0**! This AI was designed to provide companionship, learning opportunities, and emotional support in a fun, light-hearted manner.
