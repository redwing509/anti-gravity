# Roadmap

This is a plan, not a claim of completed work. Dates and engine choices will be updated as surveys and reviews land.

## Phase 0 — Scaffold and first literature survey (current)

- Create the public repository with an honest scope, MIT license, standing rules, and this roadmap.
- Run one Hermes `we-research` literature and engine survey (job key `ag-research-01`) on free compute.
- Fact-check every citation in that draft against opened sources.
- Publish the checked findings as `docs/RESEARCH-01.md` on branch `research/initial-survey` and open a pull request. Do not merge until James approves.
- Recommend two or three free open-source engines and a first model-only test for each. Do not install them until James says so.

## Phase 1 — Choose and install engines (needs approval)

- After the survey pull request is reviewed, install only the engines James approves, on free compute, without disturbing other jobs.
- Record versions, licenses, install footprints, and a short reproducibility note for each engine.

## Phase 2 — First model-only studies

Likely first studies, in order of testability rather than sensational claims:

1. A documented electrohydrodynamic / ionic-wind case (Biefeld-Brown class), because the force has a conventional explanation that independent fluid/electrostatic solvers can compute.
2. An EmDrive or closed microwave-cavity thermal and electromagnetic artifact check with an independent EM solver, including comparison to published null tests if geometry and data are available from legitimate sources.
3. A general-relativity check of what frame dragging and energy conditions actually predict for laboratory-scale masses and for published warp-like metrics, using a numerical-relativity or equivalent open code if one is approved.

Mach-effect, Podkletnov, and gravitomagnetic claims are in scope only when a published geometry and a free solver can represent the stated physics without inventing material properties. If they cannot, keep them in the literature register and do not fake a model.

## Phase 3 — Two-engine verification

- Re-run matched cases on a second independent engine.
- Treat agreement within about 5% as the bar for proposing a result onto `main`.
- Put raw results on `simulation-results`. Promotion to `main` still needs a pull request and James's approval.

## Standing limits

- No paid compute.
- No invented citations and no pirated papers.
- No hardware or “breakthrough” claim from simulation alone.
