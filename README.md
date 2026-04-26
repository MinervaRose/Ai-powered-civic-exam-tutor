# Agentic AI Civic Tutor for French Exam Preparation
## Integrative Educational AI System Design — Capstone Synthesis

![Python](https://img.shields.io/badge/Python-3.10-0B1F3B?style=flat&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter&logoColor=white)
![LLM](https://img.shields.io/badge/AI-LLM--Powered-6A0DAD?style=flat)
![Educational AI](https://img.shields.io/badge/Focus-Educational%20AI-FF2D95?style=flat)
![Governed Architecture](https://img.shields.io/badge/Architecture-Governed-1F3B73?style=flat)
![Human in the Loop](https://img.shields.io/badge/Design-Human%20in%20the%20Loop-8A2BE2?style=flat)
![Status](https://img.shields.io/badge/Status-Complete-2E8B57?style=flat)

---

## Project Overview

This project presents an AI-powered tutoring system designed to support preparation for the French civic integration exam.

The exam requires knowledge of institutional, legal, and cultural concepts that are often abstract and difficult for non-native speakers. Existing preparation methods rely heavily on memorization and static materials, which do not provide feedback, adaptation, or realistic exam simulation.

This project addresses this gap by designing a **governed, agentic AI tutoring system** that combines deterministic evaluation with AI-generated explanations.

The system simulates a 40-question multiple-choice exam, evaluates responses, provides bilingual feedback, and identifies weak areas, while incorporating basic governance and Human-in-the-Loop mechanisms.

This artifact represents an integration of system design, applied AI, and responsible AI principles within an educational context.

---

## What This System Demonstrates

This project demonstrates:

* Curriculum-grounded question generation and evaluation

* Deterministic scoring for reliability and consistency

* AI-generated bilingual feedback (French / English)

* Structured exam simulation (40-question workflow)

* Weak-area identification across chapters and topics

* Human-in-the-loop interaction (flagging + re-explanation)

* Lightweight governance layer for transparency and control

* Modular agentic architecture for extensibility

The emphasis is on **system design and learning orchestration**, rather than isolated model performance.

---

## System Architecture

The system follows a modular, agent-inspired workflow:

Question Selection  
→ MCQ Generation  
→ Deterministic Evaluation  
→ AI Feedback Generation  
→ Weak Area Analysis  
→ Final Report Generation  
→ Governance Layer (Flagging + Explanation Control)

### Core Agents

* **QuestionAgent**  
  Selects questions from the curriculum dataset  

* **MCQAgent**  
  Generates multiple-choice options with coherent distractors  

* **EvaluationAgent**  
  Performs deterministic correctness evaluation  

* **FeedbackAgent**  
  Produces bilingual explanations using an LLM  

* **AdaptationAgent**  
  Identifies weak areas based on user errors  

* **FinalReportAgent**  
  Generates a final performance summary  

* **Governance Layer**  
  Enables user feedback, logging, and control  

This modular structure supports **inspectability, extensibility, and governance-aware design**.

---

## Learning Workflow

The system operates as a structured learning loop:

1. Initialize a 40-question exam session  
2. Present a question from the full curriculum  
3. Generate multiple-choice options  
4. User selects an answer  
5. System evaluates correctness deterministically  
6. AI generates bilingual explanation  
7. Score and progress are updated  
8. Weak areas are tracked  
9. Final report summarizes performance  

This workflow transforms static content into an **interactive and adaptive learning experience**.

---

## Human-in-the-Loop and Governance

This system incorporates a lightweight Human-in-the-Loop mechanism.

Users can:

* Flag responses they consider unclear or incorrect  
* Request simplified explanations  
* Interact with feedback rather than passively receiving it  

Flagged interactions are logged, creating a traceable record that supports:

* system improvement  
* accountability  
* transparency  

Additionally, prompt-level safeguards are implemented to:

* reduce hallucination risk  
* enforce factual explanations  
* maintain neutral and respectful tone  
* acknowledge uncertainty when necessary  

This ensures that governance is **embedded in the system design**, rather than added post hoc.

---

## Evaluation Summary

Evaluation is conducted at the system level.

The system tracks:

* number of correct answers  
* score over 40 questions  
* performance by chapter  
* thematic weaknesses  
* flagged interactions  

Observed behaviors include:

* consistent scoring due to deterministic evaluation  
* improved conceptual understanding through bilingual explanations  
* identification of recurring weak areas  
* user engagement through feedback and interaction  

The system functions both as an **assessment tool** and a **learning support system**.

---

## Ethical and Responsible AI Design

Ethical considerations directly shaped system design.

The system addresses:

* **Reliability**  
  through deterministic evaluation  

* **Transparency**  
  through structured feedback and logging  

* **User agency**  
  through flagging and re-explanation  

* **Bias and fairness**  
  through neutral and respectful explanation constraints  

* **Safety**  
  by limiting AI to explanation rather than evaluation  

The system is designed as a **decision-support learning tool**, not an autonomous evaluator.

Governance is implemented at both the architectural and interaction levels.

---

## Limitations

This project is an MVP focused on system design.

Current limitations include:

* Session-based adaptation only (no persistent user memory)  
* Heuristic distractor generation  
* Variable quality of AI-generated explanations  
* Limited real-time adaptation of difficulty  
* Local (non-persistent) logging of flagged cases  

Future production deployment would require:

* persistent user profiles  
* improved semantic distractor generation  
* expert validation workflows  
* long-term learning analytics  

---

## How to Run

Install dependencies:

```
pip install openai gradio
```

Open:

```
AI_Civic_Tutor.ipynb
```


Run all cells sequentially.

The notebook reproduces:

* Question generation  
* MCQ exam simulation  
* Deterministic scoring  
* AI feedback generation  
* Weak-area analysis  
* Final performance report  

No hidden state is required.

---

## Repository Structure

📓 AI_Civic_Tutor.ipynb  

📄 Dataset (JSON curriculum file)  

📄 requirements.txt  

📘 README.md  

---

## Professional Relevance

This project demonstrates applied AI system design in an educational and civic context.

It showcases:

* Integration of deterministic logic and generative AI  
* Modular agentic architecture  
* Human-in-the-loop interaction design  
* Governance-aware system thinking  
* Real-world problem framing (immigration and civic integration)  

The core competency demonstrated is:

> Designing AI systems that are not only functional, but **interpretable, controlled, and aligned with user needs**.

This project also serves as a foundation for future work in **governed AI systems for learning, decision support, and public-facing applications**.

