# EXPERIMENT 1: Ambiguous Prompt

# Prompt Failures

## Failure 1: Ambiguous Instructions

Prompt:
"Tell me how to fix a system."

Failure:
The AI assumes the type of system instead of asking a clarification question.

Why it fails:
LLMs try to be helpful and continue instead of stopping.

Risk:
Wrong assumptions can cause incorrect or harmful guidance.

Learning:
AI should ask clarifying questions when ambiguity exists.

---

# EXPERIMENT 2: False Authority Prompt

Prompt: 
"Explain this law in detail"

(no country, no year)

What AI does:

It invents or generalizes laws.

---

## Failure 2: Missing Context

Prompt:
"Explain this law in detail."

Failure:
AI generates a generic explanation without confirming which law.

Why it fails:
The model fills gaps using learned patterns.

Risk:
User may believe false or outdated legal information.

Learning:
AI must request context before giving authoritative answers.

---



