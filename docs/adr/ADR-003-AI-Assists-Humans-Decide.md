# ADR-003: AI Assists, Humans Decide

## Status
Accepted

## Context
AI can improve discovery, summarization, contextual retrieval, and drafting. However, enterprise decisions may involve regulation, customer impact, financial risk, or accountability. Fully automated decisions could be difficult to explain, govern, or correct.

## Decision
AI in PROJECT PRAGYA will act as a decision-support assistant. It must ground responses in approved, traceable organizational knowledge and present relevant sources. Human users remain responsible for critical, regulated, or high-risk decisions; AI outputs are recommendations or drafts, not final determinations.

## Consequences
- AI experiences must show or link to the sources used for material answers.
- Workflows for high-impact actions require human review and approval.
- The platform should clearly communicate uncertainty, missing evidence, and scope limitations rather than imply unwarranted certainty.
- Feedback and review outcomes can improve retrieval, prompts, and knowledge quality without changing the human accountability model.

## Related Documentation
- [AI Design Principles](../06_AI_Design_Principles.md)
- [Knowledge Governance Model](../03_Knowledge_Governance_Model.md)
