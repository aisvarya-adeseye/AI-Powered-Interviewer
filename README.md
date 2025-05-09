# Modular AI-Powered Interviewer

## Overview

This repository contains the modular components, prompt templates, and research materials for the **AI-Powered Interviewer** presented in the paper:  
**Modular AI-Powered Interviewer with Dynamic Question Generation and Expertise Profiling**  
by Aisvarya Adeseye, Jouni Isoaho, Seppo Virtanen, and Mohammad Tahir  
University of Turku, Finland.

The AI-powered interviewer is built on a **locally hosted Large Language Model (LLM)** to conduct adaptive, expertise-aware, and privacy-conscious qualitative interviews.  
It uses a structured, modular pipeline for dynamic question generation, response-driven expertise profiling, transition-aware dialogue, and redundancy avoidance.

## Repository Contents

###  Core Modules (YAML Templates)
- **M1-Generate System Prompt.yml**  
  Generates the global system prompt defining tone, ethics, flow, and rules for the LLM interviewer.
  
- **M2-Generate Initial Question.yml**  
  Selects a high-priority research area and creates the first contextual interview question for novice participants.

- **M3-Expertise Profiling.yml**  
  Analyzes participant responses and classifies expertise level (Novice, Basic Knowledge, Advanced Knowledge, Expert).

- **M4-Generate Iterative Questions.yml**  
  Generates short affirming responses, smooth transitions, and contextually relevant follow-up interview questions based on participant expertise.

- **M5-Validate Question Uniqueness.yml**  
  Ensures newly generated questions are not redundant with any prior questions.

### Research Paper
- **Dynamic_interviewer.pdf**  
  Full paper published at the ICAI'25 - The 27th Int'l Conf on Artificial Intelligence, describing system design, evaluation results, and research contributions.

## System Features
- Modular pipeline with 5 independent, reusable modules
- Local LLaMA-based LLM deployment (data privacy & GDPR-friendly)
- Expertise-aware adaptive questioning
- Dynamic response & transition generation
- Redundancy checking for non-repetitive, engaging conversations
- Fully prompt-driven architecture for flexibility and scalability

## Use Case Example
Designed and evaluated for studies on **LLM awareness and adoption among university students and professionals**.  
Can be easily adapted for other qualitative research, education, recruitment, or assessment applications.

## Reference
If you use this system in your research or projects, please cite the paper:

Aisvarya Adeseye, Jouni Isoaho, Seppo Virtanen, Mohammad Tahir. Modular AI-Powered Interviewer with Dynamic Question Generation and Expertise Profiling. University of Turku, 2025.

## Contact
For questions or collaborations:  
(mailto:aisvarya.a.adeseye@utu.fi)  
