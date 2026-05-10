# Architecture Overview

The Lead Intake AI System is a modular AI-powered automation platform designed to capture, process, analyze, and enrich client information through conversational workflows.

The system combines:
- Telegram interaction
- AI transcription
- structured lead qualification
- AI business analysis
- follow-up orchestration
- automated reporting

The architecture was designed with modularity, scalability, and conversational continuity in mind.

---

# High-Level Architecture

```text
Telegram User
      ↓
FLOW_01_TELEGRAM_INTAKE
      ↓
Google Sheets Storage
      ↓
FLOW_02_AI_ANALYSIS
      ↓
OpenAI Processing
      ↓
AI Reports & Summaries
      ↓
FLOW_03_FOLLOWUP_WINDOW