## Functional Requirement for AI-Powered Language Learning System
# 1. User Interaction & Language Portal
Users interact with the Language Portal to access Word Groups for study.
# A database of 2000 core words supports learning activities.
Users engage in various study activities, such as:

- Practice Writing Application
- Adventure Texting Game
- Sentence Constructor
- Word Guesser
- Text Completion
# 2. Sentence Constructor Study Activity
The Sentence Constructor study activity uses Retrieval-Augmented Generation (RAG) for enhanced responses.
A Vector Database stores relevant linguistic data and interacts with the internet for external references.
A Prompt Cache stores frequent prompts for efficiency.
Input Guardrails ensure appropriate and structured queries to the LLM (70B Foundation Model).
The LLM generates responses, which pass through Output Guardrails for quality assurance.
Users receive AI-generated sentence construction assistance based on their queries.
