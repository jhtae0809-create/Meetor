# MEETOR - AI-Driven Career Exploration Mentoring Platform

## 1. Project Overview
MEETOR is an AI-driven career exploration platform designed for K-12 students who are uncertain about their future paths. Moving away from a single-track, exam-focused system, MEETOR connects students with real-world professionals—including content creators, athletes, designers, chefs, and master craftsmen—through 1:1 real-time video sessions. 

Beyond simple matching, MEETOR analyzes students' strength diagnostics, aptitude tests, and self-written essays using AI to recommend the most suitable mentors. It also provides a structured 'Career Exploration Report' after each session.

## 2. CareerNet Open API Utilization
This project heavily relies on the career and occupation data provided by CareerNet (Ministry of Education, Republic of Korea) to ensure the reliability of the matching engine.

* **Target APIs:** Career Psychological Test (Aptitude, Interest, Values), Occupation Encyclopedia, and Major Information API.
* **Purpose:**
  1. To normalize students' self-introductions and behavioral data by integrating them with CareerNet's standardized occupation and major classification systems.
  2. To use highly credible K-12 public data as a standard axis for the LLM-based text analysis, ensuring the AI recommendations are reliable for parents and public education institutions.

## 3. Core Features
* **AI Mentor Matching Engine:** Automated recommendations based on LLM analysis of descriptive surveys and cosine similarity of mentor profile embeddings.
* **Real-time 1:1 Video Mentoring:** WebRTC-based online mentoring environment (includes mandatory session recording and a parental observation mode).
* **Career Exploration Report:** Automated generation of post-session reports that can be submitted to schools or integrated into official student records.
* **Minor Protection Architecture:** Built-in safety measures including mentor background checks (criminal records), legal guardian consent, and restricted in-platform communication.

## 4. Tech Stack
* **Frontend:** Responsive Web, WebRTC (Video Communication)
* **Backend & AI:** Python, LLM APIs (GPT-4/Claude/Gemini), Text Embedding Models
* **External Integration:** CareerNet Open API, Payment Gateway (PG)

## 5. Team
A 4-member team covering Business Strategy/Planning, AI & Backend Development, Frontend Development, and Marketing.
