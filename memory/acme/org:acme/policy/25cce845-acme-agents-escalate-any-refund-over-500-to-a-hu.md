---
type: Agent Memory
title: Acme agents escalate any refund over $500 to a human
description: Acme agents escalate any refund over $500 to a human
tags: [ tenant:acme, scope:org:acme, memory_type:policy ]
sources:
  - resource: verified_document:acme/policies/5
generated: { by: conformance-agent/1.0, at: 2026-09-14T15:07:31.844Z }
verified:
  - { by: human:conformance, at: 2026-09-01T00:28:00.000Z }
status: stable
key: 25cce845-1d16-4d5e-84a4-0440987b62b6
namespace: acme/org:acme
x-memgov: { candidate_id: 25cce845-1d16-4d5e-84a4-0440987b62b6, memory_type: policy, confidence: 0.8, trust_tier: human-reviewed, subject: null, attribute: null, committed_at: 2026-09-01T00:28:00.000Z, committed_by: human:conformance }
---

Acme agents escalate any refund over $500 to a human
