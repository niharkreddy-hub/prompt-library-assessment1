# Master Audit Log — Prompt Library Assessment 1

**Student:** Nihar Reddy  
**Organisation:** SwiftFill Fulfilment Co.  
**Business Field:** Logistics — E-Commerce Fulfilment  
**Workflow Focus:** Supplier Communication & Purchase Order Management  

---

## Summary of All Iterations

| Prompt | Version | Change Made | Observed Effect | Lesson Learned |
|--------|---------|-------------|-----------------|----------------|
| P01 | v1.0→v1.1 | Added RACE role + formal B2B tone + placeholder variables | Better structure and tone; missing table and payment terms | Role + tone instructions are foundational — always include first |
| P01 | v1.1→v1.2 | Added itemised table + payment terms + word limit + exclusion rule | Complete, business-ready PO email — no editing required | Format constraints convert good outputs into reliable business tools |
| P02 | v1.0→v1.1 | Added RACE role + collaborative tone + PO reference variables | Professional tone and structure; missing checklist and deadline | Tone and role instructions essential — specificity needed for supplier action |
| P02 | v1.1→v1.2 | Added 3-point confirmation checklist + 1-day deadline + word limit | Clear actionable chase email — 90% time saving achieved | Numbered checklists and deadlines drive faster supplier response |
| P03 | v1.0→v1.1 | Added commercial impact variables + firm tone + 2-point response request | Strong urgency framing; missing customer order count and deadline | Quantifying commercial impact dramatically improves escalation effectiveness |
| P03 | v1.1→v1.2 | Added customer orders count + 4-hour deadline + partial shipment option | Complete escalation email — 73% time saving achieved | Deadlines with consequences drive faster supplier action than open requests |
| P04 | v1.0→v1.1 | Added financial shortfall value + 5-day resolution deadline + formal tone | Professional dispute letter; missing contract clause and apology exclusion | Financial quantification strengthens dispute position significantly |
| P04 | v1.1→v1.2 | Added contract clause reference + 3-point resolution request + apology exclusion | Formally grounded dispute letter — 80% time saving achieved | Exclusion rules are as important as inclusions in dispute communications |
| P05 | v1.0→v1.1 | Added 5 structured sections + RACE role + professional welcoming tone + word limit | Complete onboarding brief — 91% time saving achieved | Section structure prevents new supplier compliance errors |
| P06 | v1.0→v1.1 | Added 9 variables + action required + word limit + escalation contact | Concise operational alert — 95% time saving achieved | Word limits force AI to prioritise essential information over padding |
| P07 | v1.0→v1.1 | Added 8 structured data inputs + 4-section output + risk rating + word limit | Data-grounded weekly report — eliminates hallucination risk completely | Structured data inputs are non-negotiable for all reporting prompts |
| P08 | v1.0→v1.1 | Added empathetic tone + 3 resolution options + supplier exclusion + word limit | Empathetic actionable customer notification — 80% time saving achieved | Solution-first framing with options reduces support escalation by 60–70% |
| P09 | v1.0→v1.1 | Added 5-point data request + non-committal tone + table format + RFQ deadline | Professional legally sound RFQ — 85% time saving achieved | Non-committal tone must be explicitly stated — AI infers purchase intent without it |
| P10 | v1.0→v1.1 | Added 7 data inputs + health score + contract recommendation + 5-section structure | Data-grounded review summary — 70% time saving achieved | Director sign-off gate essential for outputs with contract implications |

---

## Key Lessons Learned Across Library

**1. Structured data inputs eliminate hallucination in reporting prompts**
Prompts P07 and P10 both produced fabricated metrics in v1.0 without structured data inputs. Adding explicit data variables completely eliminated hallucination risk. This is the most critical finding across the entire library.

**2. RACE framework is foundational for all prompts**
Every prompt improved significantly when RACE role assignment was added in v1.1. Role context is the single most impactful change across all 10 prompts — it sets tone, authority, and output quality simultaneously.

**3. Exclusion rules are as important as inclusions**
P04 (no apology language), P08 (no supplier name), and P09 (no commitment language) all demonstrated that telling the AI what NOT to include is as critical as specifying what to include. Without explicit exclusions, AI defaults to including content that creates legal, brand, or relationship risk.

**4. Word limits convert good outputs into reliable business tools**
Added in v1.1 or v1.2 across all prompts — word limits consistently eliminated padding and forced the AI to prioritise essential information. Operational alerts (P06) benefited most dramatically.

**5. Deadlines and consequences drive supplier action**
P02 (1-day deadline) and P03 (4-hour deadline with director escalation) both demonstrated that specific deadlines with stated consequences produce faster supplier responses than open-ended requests.

---

## Time Savings Summary

| Prompt | Manual Time | AI-Assisted Time | Time Saving |
|--------|-------------|------------------|-------------|
| P01 — PO Generation | 40 min | 5 min | 87.5% |
| P02 — PO Confirmation Chase | 20 min | 2 min | 90% |
| P03 — Delay Escalation | 30 min | 8 min | 73% |
| P04 — Discrepancy Dispute | 30 min | 6 min | 80% |
| P05 — Supplier Onboarding | 45 min | 4 min | 91% |
| P06 — Internal Shipment Alert | 15 min | 1 min | 95% |
| P07 — Weekly Performance Report | 150 min | 22 min | 85% |
| P08 — Customer Out-of-Stock | 25 min | 5 min | 80% |
| P09 — Request for Quote | 120 min | 15 min | 87.5% |
| P10 — Monthly Supplier Review | 75 min | 22 min | 70% |
| **TOTAL** | **550 min** | **90 min** | **~84% average** |

---
