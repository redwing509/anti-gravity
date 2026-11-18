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
