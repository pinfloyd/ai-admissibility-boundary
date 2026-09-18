# Current public demonstration authority model

## Purpose

This document describes the current public demonstration contract for AI Admissibility.

The goal is to prove that a real external boundary can decide before a protected effect without exposing unrestricted authority access through the browser.

## Canonical identity

The current installed boundary used by the public demonstration is:

`AI_BOUNDARY_RELEASE_V1`

The official demonstration surface is:

https://ai-admissibility.com/canonical-pilot/

## Public demonstration rule

The browser is intentionally restricted.

It may submit only the fixed public demonstration scenario exposed by the canonical pilot.

The browser does not receive:

- unrestricted authority credentials;
- direct access to the isolated protected-effect mechanism;
- a generally open public key endpoint;
- arbitrary ALLOW capability.

## Public gate behavior

The current public contract intentionally treats the external gate as protected:

- the public identity endpoint is protected;
- anonymous admission is rejected;
- the canonical pilot uses a restricted bridge to the installed boundary;
- the demonstration returns a signed decision before the protected test effect.

A protected or rejected public request is therefore not evidence that the installed boundary is unavailable.

## Current proof shape

The live canonical pilot demonstrates a fixed known-DENY case.

Separately, the public evidence surface may describe a controlled proof in which one exact signed ALLOW was consumed for one exact isolated effect.

Those two facts must not be generalized into a claim that every deployment is non-bypassable.

## What the public demonstration does not provide

- no public checkout;
- no payment or paid-tier transition;
- no automatic credential or token issuance;
- no unrestricted general-use authority API;
- no customer production runtime;
- no universal safety, security, legal, or compliance guarantee.

## Real deployment requirement

A real integration needs its own evidence that:

1. the protected action is precisely defined;
2. admission is evaluated by a separate authority before that action;
3. the returned decision is verified;
4. DENY or unverifiable admission blocks execution;
5. no alternate path bypasses the admission dependency to reach the same protected effect.

## Historical note

Earlier versions of this document described a three-run demonstration authority, demo credentials, metering, and a paid transition.

Those ideas belong to an earlier design stage and are not the current public contract.

**No Admission = No Execution.**
