# State Machine

The platform uses internal workflow states to manage lead progression.

---

# Main States

| State | Description |
|---|---|
| FLOW1_ACTIVE | User is answering intake questions |
| FLOW1_DONE | Intake completed |
| FLOW2_PROCESSING | AI analysis running |
| FLOW2_READY | AI analysis completed |
| FLOW3_WAITING | Additional information window open |
| FLOW3_CLOSED | Follow-up window closed |
| FINAL_READY | Final result prepared |

---

# Workflow Progression

```text
FLOW1_ACTIVE
      ↓
FLOW1_DONE
      ↓
FLOW2_PROCESSING
      ↓
FLOW2_READY
      ↓
FLOW3_WAITING
      ↓
FLOW3_CLOSED
      ↓
FINAL_READY