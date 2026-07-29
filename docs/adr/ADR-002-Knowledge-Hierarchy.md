# ADR-002: Knowledge Hierarchy

## Status
Accepted

## Context
Enterprise knowledge is drawn from policy documents, procedures, cases, reference material, and user context. These sources vary in authority and may overlap or conflict. Retrieval without an explicit precedence model can surface outdated or less reliable information.

## Decision
PROJECT PRAGYA will classify knowledge by source type and apply a defined hierarchy when presenting or using it. For overlapping information, the platform will prioritize:

1. Approved policy documents
2. Current operational procedures
3. Reviewed precedent cases
4. Properly statused user-generated notes or drafts

The hierarchy will distinguish strategic knowledge, operational knowledge, case knowledge, and user context. Source authority, approval status, and recency must be available as metadata for retrieval and AI grounding.

## Consequences
- Ingestion processes must capture source type, owner, approval status, effective date, and version metadata.
- Search and AI retrieval must favor authoritative, current sources when content conflicts.
- Lower-priority contextual knowledge can assist users but cannot silently override approved policy.
- Content owners need processes for reviewing, retiring, and replacing stale material.

## Related Documentation
- [Knowledge Sources and Hierarchy](../04_Knowledge_Sources_and_Hierarchy.md)
- [Enterprise Information Architecture](../02_Enterprise_Information_Architecture.md)
