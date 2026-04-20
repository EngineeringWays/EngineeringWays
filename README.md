# ⚡ EngineeringWays Data Lab: Circuit Analysis Reasoning Dataset (Free Sample)

[![Premium Dataset](https://img.shields.io/badge/💎_Get_the_Master_File_(592_Items)-Click_Here-blue?style=for-the-badge)](https://payhip.com/b/GRPY0)

This is a free **50-item sample** of the EngineeringWays Circuit Analysis Reasoning Dataset. It is designed specifically for fine-tuning Large Language Models (LLMs) in advanced STEM problem-solving, featuring strict Chain-of-Thought (CoT) reasoning.

**Want the complete, deduplicated 592-item master dataset?** 👉 **[Get the LoRA-Ready Master File on Payhip](https://payhip.com/b/GRPY0)**

---

## 🚀 Dataset Overview
Most math and physics datasets provide a question and a direct answer, causing models to hallucinate complex calculations. This dataset is engineered differently. 

Every single entry forces the AI to "think" before it answers, mapping out KVL/KCL equations, identifying supernodes, and performing algebraic substitutions internally before outputting the final LaTeX-formatted response.

### Key Features of the Master File:
* **True Chain-of-Thought:** Utilizes `<think>...</think>` tags for internal reasoning.
* **Strict Textbook Formatting:** All mathematical equations and final answers are wrapped in industry-standard LaTeX (`$...$` and `$$...$$`).
* **Complex Domains:** Covers Nodal Analysis, Mesh Analysis, Thevenin/Norton Equivalents, Superposition, and Ideal Op-Amps.

---

## 🔬 Methodology & Quality Control
To ensure absolute mathematical precision and structural variety, this dataset was built using a rigorous multi-step pipeline:
* **Advanced Synthesis & Verification:** Core problems and logical reasoning traces were generated and cross-validated using a dual-model approach featuring **Gemini Pro** and **DeepSeek**.
* **Algorithmic Deduplication:** Raw generations were processed through custom Python scripts to aggressively filter out identical topologies, overlapping numerical values, and low-quality or repetitive outputs. The result is 592 perfectly unique, high-signal items.
* **Format Standardization:** Automated formatting scripts ensured 100% compliance with standard JSONL structures and LaTeX math wrapping.

---

## 🛠️ Data Structure
The dataset is in `.jsonl` format, natively ready for Hugging Face `datasets` ingestion and Unsloth / LoRA fine-tuning pipelines.

**Format:**
```json
{
  "instruction": "You are an expert engineering tutor...",
  "input": "[Detailed circuit topology and component values]",
  "output": "<think>\n[Internal step-by-step algebraic reasoning]\n</think>\n\n[Final textbook-style explanation with LaTeX equations]"
}
```

---

## 📈 Upgrade to the Master File
This 50-item sample is perfect for testing your formatting pipeline. To achieve actual performance gains in STEM reasoning, you need the full volume and variance of the master dataset. 

**[🔗 Download the 592-Item Master Dataset Here](https://payhip.com/b/GRPY0)**

*Produced by EngineeringWays Data Lab. High-signal data for advanced AI.*
