# Google Sheets Schema

The system uses Google Sheets as an initial lightweight database layer.

---

# Main Tables

## Leads

Stores:
- user information
- intake progress
- AI summaries
- workflow states
- timestamps

---

## Flow2_Extras

Stores:
- additional user information
- extra transcripts
- follow-up messages
- supplemental context

---

# Main Relationships

```text
Leads
   ↓
Flow2_Extras