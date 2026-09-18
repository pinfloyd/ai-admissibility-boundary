# Hosted Authority — historical/reference concept

## Current canonical status

AI Admissibility has a canonical installed boundary used for controlled public demonstration and proof.

Current installed authority identity:

`AI_BOUNDARY_RELEASE_V1`

Official public surface:

https://ai-admissibility.com/

Canonical live demonstration:

https://ai-admissibility.com/canonical-pilot/

This repository is not the installed runtime and does not provide public customer authority access.

## Historical context

Earlier project stages used the term **Hosted Authority** for a proposed commercial or customer-specific authority service.

That historical design line is retained for reference, but it is not the current public product contract.

The current website and GitHub repositories are showcase, documentation, proof, and demonstration surfaces.

They do not provide:

- checkout or payment processing;
- automatic credential issuance;
- an unauthenticated production authority endpoint;
- customer production execution.

## What remains technically relevant

The architectural idea remains the same:

- execution intent is formed by a requester;
- a separate authority evaluates admission before protected execution;
- the authority returns a signed ALLOW or DENY decision;
- the integration must fail closed when admission is denied, missing, invalid, stale, expired, or unverifiable;
- a signed ALLOW is authority to proceed under the agreed scope, not execution itself.

## Public proof distinction

Anonymous rejection by the public gate is expected behavior.

The public identity endpoint is intentionally protected.

Public Marketplace evaluation is not a customer-specific production no-bypass guarantee.

## Collaboration

For research, integration, collaboration, or deployment discussions:

**governance@ai-admissibility.com**

**No Admission = No Execution.**
