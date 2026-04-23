# VeriAjo TODO

This file is the submission-readiness checklist for the VeriAjo paper.

## 0. Strategic lock-in

- [ ] Confirm the exact novelty statement in one sentence
- [ ] Decide whether the paper is primarily about:
  - [ ] adaptive governance for group finance
  - [ ] verifiable payout / contribution policy enforcement
  - [ ] hardship-aware financial flexibility
- [ ] Decide the target venue and page limit
- [ ] Confirm the paper is a distinct publication from the earlier PureAjo work

## 1. Manuscript structure

- [ ] Finalize title
- [ ] Finalize abstract
- [ ] Make introduction answer three questions clearly:
  - [ ] why this work exists
  - [ ] why now
  - [ ] why it matters
- [ ] Ensure the contribution list is specific and non-overlapping
- [ ] Keep the problem statement narrow and realistic
- [ ] Avoid overpromising implementation detail that the paper does not yet show

## 2. Core technical story

- [ ] Define the adaptive policy model precisely
- [ ] Specify what can change dynamically:
  - [ ] contribution deferral
  - [ ] payout priority
  - [ ] hardship handling
  - [ ] member standing / trust state
- [ ] Define what stays fixed:
  - [ ] auditability
  - [ ] replayability
  - [ ] rule transparency
- [ ] State the trust model clearly
- [ ] State how disputes are reconstructed

## 3. Evaluation plan

The paper must prove that adaptive governance is actually useful.

- [ ] Define the baseline systems to compare against
- [ ] Choose metrics that reflect the claim:
  - [ ] fairness / consistency
  - [ ] replayability
  - [ ] dispute clarity
  - [ ] default resilience
  - [ ] governance overhead
- [ ] Decide whether the evaluation is:
  - [ ] simulation-only
  - [ ] prototype + simulation
  - [ ] prototype + small pilot
- [ ] Make sure the evaluation matches the ambition of the venue

## 4. Evidence needed before submission

- [ ] A crisp novelty paragraph
- [ ] A precise motivation paragraph
- [ ] A figure showing the adaptive governance flow
- [ ] A table comparing VeriAjo to fixed-rule and manual governance baselines
- [ ] A paragraph explaining why the system matters in the world today
- [ ] At least one concrete scenario showing hardship handling or payout adaptation

## 5. Writing discipline

- [ ] Remove generic blockchain language that does not add value
- [ ] Remove any claims that are not backed by the paper
- [ ] Keep the paper short, direct, and defensible
- [ ] Make sure the contribution is about governance and adaptability, not just digitization
- [ ] Ensure the paper reads like a new work, not a rename of PureAjo

## 6. Submission hygiene

- [ ] Confirm bibliography is complete
- [ ] Compile cleanly from a fresh clone
- [ ] Verify all generated artifacts are ignored or excluded appropriately
- [ ] Keep only the source files under version control
- [ ] Prepare repo URL and submission notes

## 7. Open questions to resolve

- [ ] What is the exact target venue?
- [ ] Do we have enough implementation detail to support the novelty claim?
- [ ] Is the evaluation strong enough, or do we need a prototype?
- [ ] Should the paper emphasize group savings, mutual aid, or microinsurance more strongly?
- [ ] Should the naming stay as VeriAjo, or should we refine the brand further?

## Suggested order of work

1. Lock novelty
2. Lock venue
3. Lock evaluation
4. Then rewrite the manuscript top-down

If any of the first three are fuzzy, stop and resolve them before adding more prose.
