# AlevelHelper
An AI assistant for A Level learning helper, powered by InternLM

---

AlevelHelper is a comprehensive study assistant designed to help students achieve top grades (A*) in their A-level exams. By leveraging intern-powered data and advanced AI technologies, AlevelHelper provides personalized guidance, practice questions, and detailed explanations to ensure success.

---

## Architecture
### 1. Data Collections

Books: Collection of textbooks and reference materials.
Specification: Official exam specifications and guidelines.
Papers: Past exam papers and sample questions.
### 2. Preprocessing

Key Words: Extraction of key terms and concepts from the collected data.
QA Chains: Generation of question-answer pairs for practice.
Data Generation Tool Chain: Automated tools for creating new practice questions and scenarios.
### 3. Model Finetuning

InternLM-2.7b: Base model for natural language processing.
Xtuner: Fine-tuning tool to optimize the model for specific tasks.
LMDeploy quantization: Deployment of the fine-tuned model.
Qlora: Additional fine-tuning techniques to enhance performance.
### 4. Deploy

TurboMind: Deployment platform for efficient and scalable deployment.
Application: Final application that integrates all components.
### 5. Application Construction

ChatTTS: Chat-based text-to-speech functionality for interactive learning.
ChatBOT: AI chatbot for answering questions and providing explanations.
### 6. Application Experience

OpenLab: Open-source laboratory for continuous improvement and community contributions.
Streamlit: Framework for building user-friendly applications.


![alHelp](https://github.com/user-attachments/assets/a29baf4b-3cb8-4103-a1ec-a0864c3ac6ab)
