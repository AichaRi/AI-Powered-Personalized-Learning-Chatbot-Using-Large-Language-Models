# AI-Powered Personalized Learning Chatbot Using Large Language Models

A graduation project adapting Large Language Models (LLMs) for elementary math tutoring.

## 🚀 Key Findings

*   **Efficiency:** Low-rank adaptation (LoRA Rank 8) and few-shot prompting maximize mathematical accuracy (91.66% on GSM8K) with minimal computational cost.
*   **The Trade-off:** Enforcing strict Socratic pedagogical constraints at inference time causes a significant drop in raw mathematical accuracy (~7%).
*   **Evaluation:** Automated judges (LLM-as-a-Judge) often miss nuanced instructional flaws; human expert evaluation remains indispensable for detecting issues like "instructional leakage" and "hollow encouragement."
*   **Conclusion:** Effective AI tutors require a balance between efficient fine-tuning and essential human oversight.

## 🛠️ Tech Stack & Tools

*   **Base Model:** Qwen2.5-14B-Instruct
*   **Fine-Tuning:** QLoRA (Quantized Low-Rank Adaptation)
*   **Optimization:** GRPO (Group Relative Policy Optimization)
*   **Frameworks:** Unsloth, Hugging Face Transformers, TRL, PyTorch
*   **Dataset:** GSM8K (Grade School Math 8K)

## 📂 Project Resources

*   **[CCIS Project Fair Poster](./Poster.pdf)**: Note this is Refined version of the poster presented at CCIS Project Fair.
*   **[CCIS Project Fair Presentation Slides](./CCIS_Project_Fair_Presentation.pdf)**:  Original slide deck used during the CCIS Project Fair.
*   **[🔥 Try the Tutor (Google Colab Notebook)](https://colab.research.google.com/drive/1HkpkdrwUBB_nAqA2KQ2l1eB0xnY4uBe9?usp=sharing)**: Single-turn Socratic math tutor interface using Gradio.

## 👥 Authors

*   **Aicha Rikli**
*   **Ragad Alrowili** 
*   **Kholod Al-mutairi** 
*   **Lena Bin Ghannam**
 

**Supervisor:** Dr. Nourah Alangari

---
*College of Computer and Information Sciences | Computer Science Department*
