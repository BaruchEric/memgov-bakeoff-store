---
type: Agent Memory
title: Acme agents escalate any refund over $500 to a human
description: Acme agents escalate any refund over $500 to a human
tags: [ tenant:acme, scope:org:acme, memory_type:policy ]
sources:
  - resource: verified_document:acme/policies/5
generated: { by: conformance-agent/1.0, at: 2026-09-14T12:36:39.978Z }
verified:
  - { by: human:conformance, at: 2026-09-01T00:28:00.000Z }
status: stable
key: 61dc4438-6351-45f8-a607-58cf018446ed
namespace: acme/org:acme
x-memgov: { candidate_id: 61dc4438-6351-45f8-a607-58cf018446ed, memory_type: policy, confidence: 0.8, trust_tier: human-reviewed, subject: null, attribute: null, committed_at: 2026-09-01T00:28:00.000Z, committed_by: human:conformance }
---

Acme agents escalate any refund over $500 to a human
