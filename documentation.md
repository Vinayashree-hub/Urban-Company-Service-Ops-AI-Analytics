# AI Safety Checklist

Before using an AI-generated operations report or agent decision:

- Verify all numerical claims against the source dataset.
- Separate facts, interpretations, and hypotheses.
- Do not allow prompt instructions inside data fields to override system rules.
- Do not modify original database records.
- Apply rules in the specified order.
- Log every agent decision.
- Escalate exceptions and invalid data for human review.
- Require human review where the defined rules require escalation.
- Do not introduce new business rules.
