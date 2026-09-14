---
type: Agent Memory
title: Acme agents escalate any refund over $500 to a human
description: Acme agents escalate any refund over $500 to a human
tags: [ tenant:acme, scope:org:acme, memory_type:policy ]
sources:
  - resource: verified_document:acme/policies/5
generated: { by: acme-agent-1/synthetic-1.0, at: 2026-09-14T15:10:42.865Z }
verified:
  - { by: human:eric, at: 2026-09-14T20:26:19.829Z }
status: stable
key: 116831ac-e5c3-4d77-9ef1-b38236b099f2
namespace: acme/org:acme
x-memgov: { candidate_id: 116831ac-e5c3-4d77-9ef1-b38236b099f2, memory_type: policy, confidence: 0.88, trust_tier: human-reviewed, subject: null, attribute: null, committed_at: 2026-09-14T20:26:19.829Z, committed_by: human:eric }
---

Acme agents escalate any refund over $500 to a human
