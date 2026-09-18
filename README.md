# AI Admissibility Boundary

Public architecture, proof, and demonstration surface for an external pre-execution admission boundary.

A scanner reports after or around execution. An admission boundary decides whether execution may continue.

**No Admission = No Execution.**

## Canonical source of truth

Official public product and documentation surface: https://ai-admissibility.com/

This repository is not the canonical installed runtime. It documents and demonstrates the boundary model and links back to the current public demonstration surface.

## Repository role

This repository is for:
- architecture and terminology;
- proof / evaluation material;
- bounded examples;
- public documentation for the external admission model.

It is not a commercial execution service, checkout surface, customer runtime, or claim that every public GitHub artifact is wired to the installed authority.

## Related GitHub surfaces

- Current Marketplace evaluation Action: https://github.com/pinfloyd/ai-admissibility-action
- Compatibility workflow slug: https://github.com/pinfloyd/cnp-action
- Agent + Boundary demo: https://github.com/pinfloyd/ai-admissibility-agent-boundary-demo
- Hosted Authority historical/reference package: https://github.com/pinfloyd/ai-admissibility-hosted-authority

For new evaluation installs, use **ai-admissibility-action**. The `cnp-action` repository is retained for compatibility with existing references and is not the canonical new-install surface.

## Current boundary status

The project has a canonical installed boundary used for controlled public demonstration and proof. The public endpoint is intentionally gated; anonymous access is not equivalent to authority health.

This repository does not expose secrets, activation tokens, private enforcement logic, payment infrastructure, or customer-specific production bindings.

## Collaboration

The website and GitHub repositories are public showcase and demonstration surfaces only.

They are not used to sell access, issue credentials, process payments, or run customer production workloads.

For collaboration or deployment discussions, contact:

**governance@ai-admissibility.com**

## Platform-native policy vs external admission

Pre-run policy is necessary. External admission is the stronger boundary.

Platform-native controls improve the executor. External admission separates execution from authority.

If execution can proceed without an external allow decision, the system has policy, but not external admission authority.

**Surrogate Boundary Test:** Can execution proceed without an external allow decision?

Learn more:
- https://ai-admissibility.com/platform-native-policy/
- https://ai-admissibility.com/external-admission-authority/
- https://ai-admissibility.com/surrogate-boundary-test/
- https://ai-admissibility.com/canonical-terms/
