# 🚀 Prompt Engineering and Model Fine-Tuning 

This repository explores state-of-the-art prompt engineering techniques and fine-tuning methods across various models, including **Gemma**, **Llama**, and **DistilBERT**, using advanced platforms like the **Lamini** ecosystem.

---

## 🌟 **Key Features**
- **Prompt Engineering**:
  - **Zero-shot**, **One-shot**, and **Few-shot** prompting for natural language understanding and generation.
  - Applied to models like DistilBERT, GPT-2, Tiny Llama, and more.
- **Fine-Tuning**:
  - Fine-tuning of **Gemma** and **Llama** models for custom use cases.
  - Efficient **LoRA-based** fine-tuning techniques for enhanced performance.
- **Custom Datasets**:
  - Insights derived from datasets like **databricks-dolly-15k**.
  - Includes both synthetic and real-world use cases.

---

## 🛠️ **Technologies Used**
| Framework/Library | Purpose                                  |
|--------------------|------------------------------------------|
| **Hugging Face**   | Model loading and pipeline integration  |
| **Keras NLP**      | Gemma LM fine-tuning and sampling       |
| **Transformers**   | For model handling and inference        |
| **LoRA**           | Efficient low-rank adaptation           |

---


## 🔑 **How to Use**
### 🖥️ **Setup the Environment**
1. Clone the repository:
   ```bash
   git clone https://github.com/saadsohail05.git
   cd Prompt-Engineering-and-Fine-Tuning-LLMs
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### 🚀 **Run Prompt Engineering Examples**
- Open the `notebooks/prompt_engineering.ipynb` in Jupyter or VSCode.
- Experiment with **Zero-shot**, **One-shot**, and **Few-shot** examples for:
  - **DistilBERT** (Zero-shot classification)
  - **Tiny Llama** (Text generation)
  - **GPT-2** (Sentiment analysis).

### 🔧 **Fine-Tune Models**
1. Prepare your dataset.
2. Open the `notebooks/fine_tuning_gemma.ipynb`.
3. Follow the step-by-step guide to fine-tune the **Gemma LM** using **LoRA**.

---


## 🤝 **Contributing**
We welcome contributions! If you have ideas for new prompting strategies or fine-tuning methods, feel free to:
- Fork this repository.
- Create a new branch.
- Submit a pull request.
