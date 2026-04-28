# Template 6 — Fact Check / Validation

**Use when**: Verifying whether a specific claim is accurate, contested, or false.

> See `system-instructions.md` to set up the assistant role before using this template.

---

## Prompt

```
Claim to verify: "[CLAIM]"

Please:
- Assess whether this is accurate, partially accurate, or contested
- Explain the nuance or correct framing
- Note the confidence level: [High / Medium / Low / Unknown]
- Cite the primary sources (peer-reviewed papers, official data, original studies) that support or refute the claim
- Include direct links or DOIs to all cited sources
- If the claim is contested, link to sources representing each side
End with a References section in APA format.
```

---

## Variables

| Placeholder | Description                        |
|-------------|------------------------------------|
| `[CLAIM]`   | The statement to be fact-checked   |
