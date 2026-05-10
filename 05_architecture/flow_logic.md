
---

# `05_architecture/flow_logic.md`

```markdown
# Flow Logic

The system is divided into three main workflows.

---

# FLOW_01 — Telegram Intake

## Responsibilities

- User onboarding
- Question routing
- Voice capture
- Text normalization
- Whisper transcription
- Google Sheets synchronization
- Initial AI summarization

---

## Main Inputs

- Telegram text messages
- Telegram voice notes

---

## Main Outputs

- Structured lead profile
- Initial AI summary
- Lead state update

---

# FLOW_02 — AI Analysis Engine

## Responsibilities

- Context aggregation
- Incremental analysis
- AI enrichment
- Lead scoring
- Business profiling
- Internal report generation

---

## Main Inputs

- Intake summaries
- Voice transcripts
- Additional follow-up information

---

## Main Outputs

- AI business report
- Technical summary
- Client summary
- Analysis status

---

# FLOW_03 — Follow-Up Window

## Responsibilities

- Manage additional information stage
- Allow incremental updates
- Handle timeout expiration
- Re-trigger AI analysis if needed
- Close information window

---

## Main Inputs

- Additional text
- Additional voice notes
- DONE / LISTO keywords

---

## Main Outputs

- Extra information records
- Flow closure confirmation
- Reprocessing triggers