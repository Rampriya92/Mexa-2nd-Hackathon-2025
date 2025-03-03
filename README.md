# Mexa-Hackathon
# Multi-Agent LLM for Cognitive Distortion and Mood Screening  
‘Insight box’ is an AI system proposed for the 2025 **[MEXA](https://mexa.app/about-us)** 2nd hackathon, it evaluates if a  Multi-Agent LLM identifies cognitive distortions and mood fluctuations in a simulated month-long individual journal. It was acknowledged by MEXA with "Honarable mention". 

Author: Ram Priyadharshini Ramachandran

## Environment Setup  
This project runs on **Google Colab**.  

## Files  
- **[Journal Generator.ipynb](https://colab.research.google.com/drive/1seJBtV8bknMxI2Hp8vxURWFwn5u8sSf5?usp=sharing)** – Generates a simulated month-long journal with varied emotional tones.  
- **[Multi Agent Screening.ipynb](https://colab.research.google.com/drive/1mZHELhkJpRcCDHkSdmyvMNcTlvy4G-Jh?usp=sharing)** – Uses a Multi-Agent LLM to analyze journal entries for cognitive distortions and mood trends.  
- **[journal_entry.txt](journal_entry.txt)** – Sample journal file for testing the model.  

## Project Overview  
This project explores how a **Multi-Agent LLM** detects **cognitive distortions** and **mood fluctuations** in a simulated month-long individual journal. The goal is to develop a **preemptive strategy** for identifying and managing **depression and anxiety**, offering insights into mental health trends over time.  

The proposed system features two LLM agents. The first LLM agent named ‘Watson’ analyses and responds to the current journal entry and gives feedback on cognitive distortions and mood on the quered entry. In contrast, the second LLM agent named “Sherlock” compares Watson analyses of the recent entry to previous ones to track changes or patterns over time. Present both immediate feedback (LLM 1) and long-term trends (LLM 2) to the user. Both LLM's were implemented using Gemini Generative AI.
To view the prototype being built using LangGraph check here <https://github.com/Rampriya92/Insight-Box/tree/main> 

<img src="https://github.com/user-attachments/assets/21c7ce1d-6d0a-464b-bd1e-6c137ba246fb" width="300"/>




## Presentation  
[View the Presentation](https://docs.google.com/presentation/d/1nhYHsb1yFmGZ3mNETs_Igq-GEx27BHaAjgssCIJXVnA/edit?usp=sharing)  

---

