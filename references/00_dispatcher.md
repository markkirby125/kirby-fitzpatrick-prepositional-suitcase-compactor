# Prepositional Suitcase Compactor — Technical Operational Dispatcher

**Framework Author**: William Fitzpatrick (*Writer Science*)  
**Source Lecture**: [Watch this if you want to IMPROVE the way you write](https://www.youtube.com/watch?v=LAmzkEyt60E)  
**Parent Collection**: [Master Collection](../../kirby-fitzpatrick-writers-collection/SKILL.md) | [Global Help](../../../kirby-help/SKILL.md)  

---

## 1. Cognitive Foundation: The Prepositional Suitcase

A "suitcase sentence" stuffs noun phrases inside nested prepositional modifiers (*of*, *for*, *in*, *with*, *to*, *by*). Instead of a direct subject-verb relationship, the reader must unpack layer after layer of prepositional packaging like Russian nesting dolls.

```text
[Nested Prepositional Suitcase: 4 prepositions]
"The configuration of the cache for the service of the auth cluster in us-east."
                  ^^^^        ^^^^         ^^^^                 ^^

[Compacted Architecture Compound: 0 prepositions]
"The us-east auth cluster's cache configuration."
```

Packing too many prepositions forces the brain to calculate hierarchical ownership backward. Compacting prepositions into compound nouns or active verbs restores reading velocity.

---

## 2. Core Compaction Techniques

### Rule 1: The 2-Preposition Threshold
Flag any sentence containing **3 or more consecutive prepositional phrases**. Compact at least two of them into compound nouns, adjectives, or possessives.

### Rule 2: Reverse-Noun Compaction
Fold `[Noun A] of [Noun B] for [Noun C]` into possessive compound structures:

| Unpacked Suitcase (Prepositional Bloat) | Compacted Form |
|---|---|
| `The utilization of resources in the pool` | `Pool resource usage` |
| `The persistence of tokens in the memory store` | `In-memory token persistence` |
| `The latency of responses from the upstream API` | `Upstream API response latency` |
| `A check on the validity of certificates for TLS` | `A TLS certificate validity check` |
| `The termination of sessions of users by the admin` | `Admin termination of user sessions` |

### Rule 3: The Verb Release Protocol
When prepositions attach to nominalizations, unroll the phrase into an active clause rather than a compound noun:
* **Suitcase**: *"The generation of reports by the billing engine occurs at midnight."*
* **Verb Release**: *"The billing engine generates reports at midnight."*

---

## 3. Engineering Application Scenarios

### 3.1 Architecture Decision Records (ADRs)
* **Suitcase**: *"We observed degradation in the throughput of the ingestion pipeline of the telemetry service."*
* **Compacted**: *"We observed telemetry ingestion pipeline throughput degradation."* (Or: *"The telemetry ingestion pipeline lost throughput."*)

### 3.2 Code Review Comments
* **Suitcase**: *"Please extract the logic for the transformation of timestamps into a helper in the utils package."*
* **Compacted**: *"Please extract timestamp transformation into a `utils` helper."*

### 3.3 API Documentation & Schema Descriptions
* **Suitcase**: *"This field represents the timestamp of the expiration of the refresh token of the user."*
* **Compacted**: *"This field stores the user's refresh token expiration timestamp."*

---

## 4. Verification Checklist

- [ ] Does any clause contain 3 or more stacked prepositions (*of*, *in*, *for*, *with*)?
- [ ] Have chains of *"of the [X] of the [Y]"* been folded into compound nouns?
- [ ] Have nominalized prepositions (*"the creation of [X] by [Y]"*) been liberated into active verbs (*"[Y] creates [X]"*)?
- [ ] Is the resulting sentence lean and fast without sounding like unnatural jargon?
