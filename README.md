# AI-Powered Personalized Learning Chatbot Using Large Language Models

A graduation project designed to adapt Large Language Models (LLMs) for elementary math tutoring. This research addresses the trade-off between mathematical accuracy and pedagogical effectiveness.

## 🚀 Key Findings

*   **Efficiency:** Low-rank adaptation (LoRA Rank 8) and few-shot prompting maximize mathematical accuracy (91.66% on GSM8K) with minimal computational cost.
*   **The Trade-off:** Enforcing strict Socratic pedagogical constraints at inference time causes a significant drop in raw mathematical accuracy (~7%).
*   **Evaluation:** Automated judges (LLM-as-a-Judge) often miss nuanced instructional flaws; human expert evaluation remains indispensable for detecting issues like "instructional leakage" and "hollow encouragement."
*   **Conclusion:** Effective AI tutors require a balance between efficient fine-tuning and essential human oversight.

## 🛠️ Tech Stack & Tools

Built using state-of-the-art parameter-efficient fine-tuning and reinforcement learning techniques:

*   **Base Model:** Qwen2.5-14B-Instruct
*   **Fine-Tuning:** QLoRA (Quantized Low-Rank Adaptation)
*   **Optimization:** GRPO (Group Relative Policy Optimization)
*   **Frameworks:** Unsloth, Hugging Face Transformers, TRL, PyTorch
*   **Dataset:** GSM8K (Grade School Math 8K)

## 📂 Project Resources

*   **[Project Poster (Final)](./Poster.pdf)**: Updated visual summary of the research.
*   **[Fair Presentation Slides](./CCIS_Project_Fair_Presentation.pdf)**: Slide deck used during the CCIS Project Fair.
*   **[🔥 Try the Chatbot (Colab)](https://colab.research.google.com/drive/1HkpkdrwUBB_nAqA2KQ2l1eB0xnY4uBe9?usp=sharing)**: Run the Socratic math tutor interactively in Google Colab using the Gradio interface.


*This project was featured at the CCIS Project Fair.*

## 👥 Authors

*   **Aicha Rikli**
*   **Ragad Alrowili** 
*   **Kholod Al-mutairi** 
*   **Lena Bin Ghannam**
 

**Supervisor:** Dr. Nourah Alangari

---
*College of Computer and Information Sciences | Computer Science Department*
