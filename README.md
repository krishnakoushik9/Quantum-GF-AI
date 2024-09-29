# 🔬 Quantum Girlfriend v1.0: DramaFusion AI

Welcome to the Quantum Girlfriend v1.0 project repository! This cutting-edge AI project leverages advanced natural language processing techniques to create a unique conversational experience by fine-tuning a large language model with the personality traits of a "possessive girlfriend" inspired by C-dramas and K-dramas.

## 🚀 Project Overview

Quantum Girlfriend v1.0 is an experimental AI project that explores the intersection of large language models, personality emulation, and cultural-specific dialogue patterns. By fine-tuning the Llama 3.1 8-billion-parameter model with meticulously curated data from popular Asian dramas, we aim to create an AI companion with a distinct and engaging persona.

### 🌟 Key Features

- 🤖 Fine-tuned Llama 3.1 8B model
- 💻 Training dataset derived from C-drama and K-drama subtitles
- ⚡ Utilizes LoRA and Unsloth for efficient fine-tuning on Google Colab
- 💾 Generates a quantized GGUF file for high-performance interaction
- 🎭 Emulates the personality of a "possessive girlfriend" character
- 🧠 Implements advanced NLP techniques for contextual understanding
- 🌐 Ollama-based deployment for easy local running

## 🛠️ Technical Stack

- **Model**: Llama 3.1 8B
- **Fine-tuning Framework**: PyTorch with LoRA (Low-Rank Adaptation)
- **Optimization**: Unsloth for memory-efficient training
- **Quantization**: GGUF (GPT-Generated Unified Format)
- **Deployment**: Ollama
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
   ```
   git clone https://github.com/krishnakoushik9/Quantum-GF-AI.git
   cd Quantum-GF-AI
   ```

2. Install Ollama:
   Follow the instructions at [Ollama's official website](https://ollama.ai) to install Ollama for your operating system.

3. Install the QuantumGirlfriend model:
   ```
   ollama pull quantumgirlfriend
   ```

4. Run the model:
   ```
   ollama run quantumgirlfriend
   ```

## 🎛️ Model Training Pipeline

1. **Data Collection and Preprocessing**:
   - 🎬 Collect subtitles from popular C-dramas and K-dramas
   - 🧹 Clean and preprocess the text data
   - 🏷️ Annotate dialogues with sentiment and context labels

2. **Fine-tuning with LoRA and Unsloth**:
   - 🚀 Set up Google Colab environment (free tier)
   - 📚 Load the Llama 3.1 8B model
   - 🔧 Configure LoRA adapters for efficient fine-tuning
   - 🏋️ Train the model using Unsloth optimizations

3. **Quantization and Optimization**:
   - 📉 Quantize the fine-tuned model to GGUF format
   - 🔬 Benchmark performance and adjust quantization parameters

4. **Deployment**:
   - 📦 Package the model for Ollama
   - 🚀 Publish the model to make it available via `ollama pull`

## 🧠 LoRA and Unsloth in Google Colab (Free Tier)

### Low-Rank Adaptation (LoRA)

LoRA is a technique that significantly reduces the number of trainable parameters, making it possible to fine-tune large language models on limited hardware:

- 🎯 Focuses on updating a small set of rank decomposition matrices instead of all model parameters
- 💾 Dramatically reduces memory requirements (often by 10x or more)
- ⚡ Enables faster training and inference
- 🔄 Allows for easy swapping of adaptors for different tasks or personalities

In our Google Colab setup:
- We use a rank of 8 for LoRA adaptors
- This allows us to fine-tune the 8B parameter model within the 12GB RAM limit of Colab's free tier

### Unsloth

Unsloth is an optimization library that further enhances the efficiency of LoRA fine-tuning:

- 🚀 Provides up to 2x speedup in training
- 📉 Reduces memory usage by up to 50%
- 🧠 Implements advanced optimization techniques like quantized backward passes

In our Google Colab (free tier) setup:
- Unsloth allows us to use a larger batch size (typically 8 instead of 4)
- Enables longer training runs without hitting OOM (Out of Memory) errors
- We use 4-bit quantization for the base model to further reduce memory footprint

### Colab Workflow

1. Mount Google Drive for persistent storage
2. Install Unsloth and other dependencies
3. Load the Llama 3.1 8B model with 4-bit quantization
4. Prepare LoRA configuration (rank=8, alpha=16)
5. Use Unsloth's optimized trainer for fine-tuning
6. Save checkpoints to Google Drive every 100 steps
7. After training, merge LoRA weights and quantize to GGUF

## 💻 Usage

To interact with QuantumGirlfriend v1.0:

1. Ensure Ollama is installed and running
2. In your terminal, run:
   ```
   ollama run quantumgirlfriend
   ```
3. Start chatting with QuantumGirlfriend in the terminal interface

## 🚧 Work in Progress

- [ ] Implement advanced context tracking for multi-turn conversations
- [ ] Develop a more sophisticated emotion detection system
- [ ] Create a web-based chat interface
- [ ] Expand the training dataset with more diverse drama sources

## 🤝 Contributing

We welcome contributions to the QuantumGirlfriend project! Please feel free to submit pull requests, report issues, or suggest improvements through GitHub issues.

## 🚨 Disclaimer

QuantumGirlfriend v1.0 is an experimental AI project created for entertainment and research purposes. It is not intended to replicate or encourage unhealthy relationship dynamics. Users should interact with the AI responsibly and maintain awareness of the distinction between AI-generated responses and human interaction.

## 📞 Contact
```

For questions, suggestions, or concerns, please open an issue in this repository or contact the project maintainer at 23h51a66h2@cmrcet.ac.in

```

---

We hope you enjoy exploring and interacting with QuantumGirlfriend v1.0! Remember, it's all in good fun, and no AI can replace genuine human connections. Happy coding! 💖🤖🔬
