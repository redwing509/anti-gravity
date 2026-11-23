# Project rules

These rules follow the solid-state fan project's operating constraints and apply to all Anti-Gravity work after the initial scaffold.

## Model-only research

- This project is model-only. It tests published claims in simulation and in the literature. It does not claim a working anti-gravity device.
- A successful simulation is not experimental validation. A well-understood effect (for example ionic wind or a thermal artifact) is not a new gravitational force.
- Do not announce a positive anti-gravity result unless matched, independently checked evidence supports that exact claim.

## Compute

- Free compute only. Do not buy, rent, or automatically provision paid capacity.
- Do not start heavy-load work without an estimate of CPU, memory, runtime and storage, and without James's OK when the job would be heavy or would need more compute.
- Do not disturb other running research jobs (including fan-project simulation locks and survey loops) unless James authorizes it.
- Installing any simulation engine, compiler toolchain, or large dependency set needs James's OK first.

## Branches and review

- The initial scaffold on `main` is the only direct commit to `main`. Everything after that goes on a branch and a pull request.
- Simulation outputs and raw solver logs go on a `simulation-results` branch. An upload or a solver exit is not validation.
- A result may be proposed for `main` only after two independent engines agree within about 5% on a matched case.
- James approves merges and pushes to `main`. Do not merge or push to `main` without that approval.

## Citations and sources

- Do not invent citations, DOIs, URLs, titles, authors, years, or numbers.
- Every factual claim in a research write-up must be checkable from a source that was opened, with a quote and a URL or DOI. If a source cannot be opened, say so and write `NOT FOUND` rather than guessing.
- Do not use Sci-Hub, Library Genesis, or similar piracy sites. Prefer author preprints, theses, institute repositories, or other legitimate open copies. If only a paywalled record exists, say so and do not invent the unseen numbers.

## Secrets and safety

- Do not commit secrets, credentials, private keys, or personal data.
- Do not email, message, or comment as James unless he asks.
- Do not delete project or remote research material without James's yes.

## Coding process (adopted Nov 22, 2026)

These four practices apply to coding work on this project. They do not
replace or weaken the full review set, frozen pass rules, or James's
merge approval, which still come first. Following them does not
authorize a push or a merge.

Source: [obra/superpowers](https://github.com/obra/superpowers), pinned at
`22f0b463e7a5e579904dd6211a520321035526f7` (v7.0.2), MIT License,
Copyright (c) 2025 Jesse Vincent. Adapted guides and that LICENSE:
`docs/superpowers-adopted`. Full text: `docs/superpowers-adopted/CODING-PROCESS.md`. Exact brief
addenda: `docs/superpowers-adopted/BRIEF-TEXT.md` and `docs/superpowers-adopted/templates/`.

1. **Test-first** — For bug fixes and new behavior, write the new test
   first and run it. It must fail for the missing behavior or
   still-present bug, not a typo or a compile error in the test. Only
   then write the smallest production change. Skip typo-only and
   docs-only work. Do not edit a frozen pass rule to match a new
   result. If production code was written before that failing run,
   delete it and start from the tests.
2. **Bite-sized written plans** — For fixes that touch more than one
   behavior, more than one production file, or a "must not change"
   control case, write a short plan first. Include the goal and finding
   id, exact file paths, each behavior as its own task (failing test
   and assertions first), and a Review Focus list with a test for the
   control case most likely to be missed. Skip one-line typo or
   docs-only fixes.
3. **Receiving official review findings** — When Claude, the
   controller, PR-Agent, CodeRabbit, gitleaks, trufflehog, a board
   note, or rb.py returns findings, read the complete list before
   changing code. Verify each finding against this repo, the relevant
   toolchain, frozen pass rules, and any decision James already made.
   Accept, accept with a smaller fix, or push back with a file, test,
   and reason. If a finding conflicts with a decision James already
   made, stop and ask him. Implement accepted items one at a time and
   re-run the relevant tests after each. Informal reviews do not
   replace the official set.
4. **Systematic debugging** — For a failing gate or harness error whose
   root cause is not already written in an approved finding: (1) read
   the full error, reproduce it, and check recent diffs, pins, inputs,
   and the environment; (2) diff against a working neighbor and read
   the solver syntax or gate contract if the failure is in generated
   input; (3) test one hypothesis and one variable; (4) write a failing
   test or known-solution assertion first, apply one root-cause fix,
   and re-run the original failing command plus surrounding checks. Do
   not relax a tolerance or a frozen pass rule. If three attempts fail,
   stop and discuss. Never print secrets; do not leave temporary debug
   prints in the submitted change.

Not adopted: the upstream plugin, hooks, telemetry, mandatory
brainstorming before every already-approved fix, extra helper agents
per task, and any flow that would skip the review set or James's merge
approval.
