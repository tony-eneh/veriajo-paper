# VeriAjo Paper Repository

**VeriAjo** is the next paper track after the earlier PureAjo work: a cleaner, more explicit exploration of **verifiable adaptive group finance** for trust-aware rotational savings and mutual aid.

This repository is organized to keep the manuscript sources, references, and submission-planning context separate and easy to maintain. The goal is not just to write a paper, but to converge on a submission-ready story with a narrow, defensible contribution.

## One-line thesis

> VeriAjo makes group finance adaptive without making it opaque: contribution, payout, and hardship rules remain transparent, replayable, and auditable.

## Why this paper exists

Group finance is still a real financial infrastructure for many communities, but it is fragile when rules are manual, opaque, or inconsistently applied. VeriAjo explores how to preserve the social flexibility of group savings while making governance verifiable.

## Current manuscript direction

The paper is being developed around:

- adaptive contribution scheduling
- payout prioritization and exceptions
- hardship-aware deferral / rescheduling
- trust-aware governance
- replayable decision logs and dispute reconstruction

This is meant to be a **systems and governance** paper, not a generic blockchain paper.

## Repository layout

```text
veriajo-paper/
├── README.md            # this file
├── TODO.md              # submission-readiness checklist
└── paper/
    ├── paper.tex        # LaTeX manuscript
    ├── references.bib   # bibliography database
    └── paper.pdf       # compiled output (generated)
```

## Writing principle

Keep the paper focused on three things only:

1. **Why group finance needs stronger governance now**
2. **What VeriAjo adds that current tools do not**
3. **How we will demonstrate that claim clearly**

If a section does not help one of those three, it probably does not belong.

## Recommended paper claim

A strong framing for the paper is:

> VeriAjo introduces adaptive, auditable group finance policies that support contribution flexibility and payout governance without sacrificing transparency or replayability.

## Build

From the `paper/` directory:

```bash
pdflatex paper.tex
bibtex paper
pdflatex paper.tex
pdflatex paper.tex
```

## Status

- Manuscript: first draft in progress
- Core novelty: needs to be locked tightly
- Venue: not yet finalized
- Implementation depth: may need expansion depending on submission target

## Notes for future editing

- Do not drift into generic blockchain hype.
- Do not treat the paper as a rebrand of the earlier PureAjo manuscript.
- Keep the novelty tied to **adaptive governance + verifiable decision replay**.
- If the paper cannot show a clear benefit over fixed-rule group finance, the contribution is too weak.

## Next step

Start from `TODO.md` and lock the strategy before writing more prose.
