# RESEARCH-01 — Initial literature and engines survey (checked)

Date: 17 November 2026 (America/Los_Angeles).
Job: Hermes `we-research` / OVH DeepSeek-V4.1-Flash-1017, job key label
`ag-research-01`, mail job
`20261117-172544-anti-gravity-initial-literature-and-engi`.
Started 5:25 PM PST, ended 6:06 PM PST, about 40 minutes, exit 0.
No engine was installed. This write-up is a fact-checked summary of that draft,
not a claim of experimental validation. Merging this document does not promote
any model result; see the promotion rule in section 3.

## DeepSeek quality verdict

The draft is usable. It followed the two-pass / quote-plus-link / `NOT FOUND`
rules, did not soften null results, and did not invent a working anti-gravity
effect. I opened the sources listed below and checked the distinctive quotes
against the opened text (or, for a few HTML sites, against the official page
returned by a separate fetch).

- Distinctive quotes checked: about 45.
- Clear or unresolved quote problems: 1 (the Graham 2008 ScienceDirect abstract
  wording). That is about a 2% quote-error rate, well under a 20% "poor quality"
  bar.
- One bibliographic error: Graham et al. 2008 is cited as Physica C
  468:552–556. Crossref and ADS give volume 468, pages 383–387, same DOI,
  title, authors and year.
- One process slip: Pass 2 cites https://fenicsproject.org/ for a NumFOCUS line
  that was not in the Pass 1 source list. The DOLFINx license and repository
  quoted from GitHub still check out.
- Honest gaps kept: the 2003 Hathaway replication was not opened (HTTP errors);
  some PDF middle sections were unread; install sizes in megabytes were mostly
  `NOT FOUND`.

Graham 2008 detail: I could not open the ScienceDirect abstract (HTTP 403). I did open a
legitimate University of Canterbury author PDF,
https://spcs.canterbury.ac.nz/~physrin/papers/SuperFrameDragging2007.pdf
(preprint dated 6 July 2007). That abstract says "No frame dragging effect was
observed by us" and "at least 21 times smaller than prediction from this
theory." It does not contain the draft's "22 times" wording or the "probability
⩾95%" clause. Until the published abstract is opened, treat those two fragments
as unverified. The paper itself is real, and the independent-null conclusion is
supported by the author PDF.

## 1. What the checked literature actually says

No opened source reports a measured, replicated anti-gravity force. The pattern
on the well-instrumented claims is a small positive signal, then a tighter
apparatus, then a null or a conventional explanation.

### Biefeld-Brown / ionic wind

This is a real force in air, not a gravitational anomaly.

- "Subsequent studies confirmed that the gravitational field was unaffected, and
  that the thrust was produced by a phenomenon now known as ionic wind."
  ([Cabanas et al., Applied Sciences 12(6):2997, 2022](https://www.mdpi.com/2076-3417/12/6/2997),
  open access, checked on the official MDPI page.)
- MIT demonstrated flight with that force: "Here we demonstrate that a
  solid-state propulsion system can sustain powered flight, by designing and
  flying an electroaerodynamically propelled heavier-than-air aeroplane."
  (Xu et al., Nature 2018; PubMed abstract
  [PMID 30464270](https://pubmed.ncbi.nlm.nih.gov/30464270/), also DOI
  10.1038/s41586-018-0707-9. Abstract only; the Nature page was paywalled.)
- The 2003 Army Research Laboratory report records the force but uses a
  simple upper bound to rule out ion wind as the cause: "A simple upper limit
  on the ion wind force shows that the ion wind effect is at least three
  orders of magnitude too small." It asks for a plasma / charge-transport
  model rather than claiming gravity. ([Bahder and Fazi, arXiv physics/0211001](https://arxiv.org/pdf/physics/0211001).)
  The draft correctly leaves the 2003 vs 2022 magnitude disagreement open.

### Podkletnov rotating superconductor

The claim, from the author's preprint: "Samples placed over the rotating disk
initially demonstrated a weight loss of 0.3-0.5%." and "the shielding effect
became considerably higher and reached 1.9-2.1% at maximum."
([cond-mat/9701074](https://arxiv.org/pdf/cond-mat/9701074.pdf).)

A 2022 open-access review, quoting later work, says Hathaway, Cleveland and Bao
(2003) found "No weight modifications or gravity-like forces were detected down
to the 0.001% level," and that Woods et al. (2001) reported an unsuccessful
attempt. The same review says of Podkletnov, "even though his results have
been, until now, neither confirmed nor disproved."
([Gallerati, Modanese and Ummarino, Front. Phys. 10:941858](https://www.frontiersin.org/articles/10.3389/fphy.2022.941858/full),
DOI 10.3389/fphy.2022.941858.) Those replication numbers are secondary: the 2003
Physica C paper itself was not opened. That is a source-access gap, not
positive evidence for a gravity shield.

### Woodward Mach-effect thruster

Claimants' NIAC Phase II report: "These devices produced on the order of 1µN of
force."
([NASA NIAC PDF](https://www.nasa.gov/wp-content/uploads/2018/03/niac_2018_phii_woodward_macheffects_2_tagged.pdf).)
Their own geometry control is in Fearn and Woodward, JSE 2(2) 2013:
"A null experiment was performed to show that all vibrational effects has been
eliminated from our data."
(https://www.tsijournals.com/articles/experimental-null-test-of-a-mach-effect-thruster.pdf;
the grammar is in the source.)

The independent TU Dresden dissertation is a null with a stated floor:
"Experiments on the double-pendulum and torsion balances with a resolution of
under 10 nN and an accuracy of 88.1 % revealed the presence of force peaks with
a maximum amplitude of 100 nN and a drift of up to 500 nN." Then: "No additional
thrust was observed above the balance drift, regardless of the driving
conditions or devices tested." The same thesis attributes the traces to
vibration transmitted to the balance beam.
([Monette, TU Dresden, defended 31 August 2023](https://tud.qucosa.de/en/api/qucosa%3A87665/attachment/ATT-0/).)

### EmDrive, including TU Dresden 2021

This is the cleanest null in the survey.

Tajmar, Neunzig and Weikert tested the NASA Eagleworks claim of
"a force of 1.2 mN/kW for an input power of 40-80 W on a torsion balance in
high vacuum," noted as "a factor of 500 higher than pure photon thrust."
They used an inverted counterbalanced double pendulum and a battery-powered
thruster to cut thermal and feedthrough artefacts. Result: "We found no thrust
values within a wide frequency band including several resonance frequencies and
different modes. Our data limit any anomalous thrust to below the force
equivalent from classical radiation for a given amount of power." And: "This
provides strong limits to all proposed theories and rules out previous test
results by at least two orders of magnitude." The classical benchmark they use
is "F/P = 1/c = 3.3 nN/W."
([CEAS Space Journal 14:31–44](https://link.springer.com/article/10.1007/s12567-021-00385-1),
DOI 10.1007/s12567-021-00385-1, volume dated 2022, online 27 July 2021, open
access. Checked on the official Springer page.)

### Tajmar gravitomagnetic / rotating-superconductor signals

The earlier positive claim: after a critical temperature "which does not
coincide with the material's superconducting temperature," rotation "could be
seen on the sensors although they are mechanically de-coupled."
([arXiv:0707.3806v9](https://arxiv.org/pdf/0707.3806v9).)

The same group's later test is a null: "No such anomalies were found within
three times the noise level of our setup (±5 × 10⁻⁸ rad s⁻¹)."
(Exponent formatting normalized.)
([Tajmar, Supercond. Sci. Technol. 24:125011, 2011](https://doi.org/10.1088/0953-2048/24/12/125011),
abstract only; checked on the IOP page.)

The 2022 review adds that in 2011 "Tajmar et al. [68] re-interpreted their
results, attributing the anomalous effects to some kind of acoustic noise,"
after new equipment "measured gyroscopes signals about 2 orders of magnitude
lower compared to earlier results," and that Graham et al. 2008 were "within
1σ from a null result." (Frontiers review above. The draft wrote "sigma" for
"σ".)

The Graham et al. paper is real (DOI 10.1016/j.physc.2007.11.011, Physica C
468:383–387, 2008). See the quality verdict for the unverified "22 times" /
"⩾95%" abstract wording. The author PDF supports a null at least 21 times
below the prediction they were testing.

### What GR and QFT are stated to permit

- Frame dragging is a standard GR effect and is tiny: "it required the analysis
  of 11 years of LAGEOS satellite orbit data to confirm Einstein's prediction
  within ±10%" (Tajmar et al.,
  [arXiv:0707.3806v9](https://arxiv.org/pdf/0707.3806v9), citing Ciufolini and
  Pavlis 2004).
- Warp-like metrics are GR solutions that need exotic matter: "By a purely
  local expansion of spacetime behind the spaceship and an opposite contraction
  in front of it, motion faster than the speed of light as seen by observers
  outside the disturbed region is possible." And: "However, just as it happens
  with wormholes, exotic matter will be needed in order to generate a
  distortion of spacetime like the one discussed here."
  ([Alcubierre, Class. Quantum Grav. 11:L73–L77, 1994](https://arxiv.org/pdf/gr-qc/0009013).)
- QFT allows local negative energy but bounds it with quantum inequalities,
  and "These results would seem to make the existence of macroscopic
  traversable wormholes very improbable."
  ([Ford and Roman, gr-qc/9510071](https://arxiv.org/pdf/gr-qc/9510071v1).)

No opened paper states that a laboratory device produced a negative-energy
density large enough for a warp-like metric, or that a rotating superconductor
does so within standard GR.

## 2. Recommended engines (do not install until James says so)

Nine free/open-source codes were checked against official pages. The first
campaign should use three small, well-documented tools that match testable
claims. Einstein Toolkit and GRChombo are real open numerical-relativity stacks
and belong in a later phase, once a concrete metric is specified; their
install footprints were `NOT FOUND` on the opened pages.

### 1. Meep (first pick for an EmDrive / cavity check)

- Developer / what it is: MIT's open-source FDTD electromagnetic solver.
  Official docs: "Meep is a free and open-source software package for
  simulating electromagnetics across a broad range of applications using the
  finite-difference time-domain (FDTD) method." It supports 1d, 2d, 3d and
  cylindrical coordinates, and MPI.
  https://meep.readthedocs.io/en/latest/
- License: GNU GPL (docs say "Free and open-source software under the GNU
  GPL"; the license page is GPL-2.0-or-later).
- Install footprint: official docs recommend Conda (`conda create -n mp -c
  conda-forge pymeep`) or `pip install pymeep`, with wheels that bundle MPB,
  Harminv, HDF5, FFTW and LAPACK. Package size and RAM were `NOT FOUND` on the
  opened page. No install has been performed.
- First test: a 3D closed tapered metal cavity driven at a documented mode.
  Report the resonance spectrum, stored energy, and surface-integrated Maxwell
  momentum flux. Pass if the computed force stays at or below the classical
  `F/P = 1/c = 3.3 nN/W` benchmark used by the Dresden EmDrive paper, and if
  any apparent excess shrinks under mesh refinement.

### 2. Elmer FEM (first pick for EHD force and thermal artefacts)

- Developer: "Elmer is mainly but not exclusively developed by CSC - IT Center
  for Science." https://www.elmerfem.org/
- What it models: "Elmer includes physical models of fluid dynamics, structural
  mechanics, electromagnetics, heat transfer and acoustics, and beyond." The
  opened homepage does not list a built-in ionization / plasma module, so it
  should not be over-claimed for full ionic-wind plasma.
- License: "Elmer was first licensed under GPL (GNU General Public License, v.
  2.1) license in 2008. Since 2012 the ElmerSolver library has been published
  under LGPL license (GNU Lesser General Public License, v. 2.0)."
  https://elmerfem.org/blog/license
  Those version numbers are as printed on the official license page and in
  `license_texts/ElmerLicensePolicy.md`. The license files in the official
  repository are `GPL-2.txt` and `LGPL-2.1.txt`.
  Source: https://github.com/ElmerCSC/elmerfem
- Install footprint: official license page states the main library is
  "libelmersolver, ~250,000 lines of Fortran code." Package size and RAM were
  `NOT FOUND`. No install has been performed.
- First test: coupled electrostatics and linear elasticity on a documented
  wire-to-plane or asymmetric-capacitor geometry, reporting net Maxwell-stress
  force; then a thermal-drift estimate for a suspended balance, compared in
  order of magnitude with the Dresden MET floor (peaks ~100 nN, drift up to
  ~500 nN). Pass if conventional electrostatic force and/or thermal drift can
  account for the observed artefact scale without new physics.

### 3. pyTDGL (first pick for a superconducting current model)

- What it is: a Python solver for a "generalized time-dependent
  Ginzburg-Landau (TDGL) model in two dimensions" for thin-film
  superconductors. Docs: https://py-tdgl.readthedocs.io/en/latest/
  Repository (not the 404 URL `pyTDGL/pyTDGL`): https://github.com/loganbvh/py-tdgl
- License: "Both SuperDetectorPy and pyTDGL are released under the open-source
  MIT License."
- Install footprint: "pyTDGL requires python 3.9, 3.10, 3.11, 3.12, 3.13, or
  3.14." Official install page says SuperLU, the default solver, "is included
  in scipy and therefore requires no additional installation," and documents
  `pip install tdgl`. Megabyte size was `NOT FOUND`. This is the smallest
  install surface of the three. No install has been performed.
- First test: a 2D thin-film disk in a perpendicular applied field, exporting
  sheet-current density. This models a current distribution that
  London-moment / gravitomagnetic claims depend on. It does not, by itself,
  simulate a gravity-modification force. Pass if the current solution is
  mesh-converged. Any comparison to a claimed gravity effect needs a formula
  copied from an opened paper; none of the opened papers supplied a usable
  quantitative target (`NOT FOUND`).

Runner-up tools, not recommended for the first install: GetDP (GPL-2+, official
binaries 3.5.0 dated 13 May 2022, https://getdp.info/), OpenFOAM Foundation
(GPLv3, ~1.5 million lines of C++, already used on the fan project), FEniCSx /
DOLFINx (LGPLv3), openEMS (GPLv3), Einstein Toolkit (open-source, component
licenses, https://einsteintoolkit.org/), and GRChombo (BSD-3,
https://github.com/GRTLCollaboration/GRChombo).

## 3. Proposed model-only first study

1. Write the falsifier for each claim before any run: EmDrive must beat
   `F/P = 1/c = 3.3 nN/W`; MET must beat the Dresden artefact envelope
   quoted from the Monette thesis in section 1 (resolution under 10 nN,
   peaks ~100 nN, drift up to ~500 nN), not the resolution figure alone;
   amplified frame dragging must beat the classical
   prediction for the chosen rotor and sensor geometry, not the LAGEOS-scale
   Earth result.
2. Meep cavity baseline (section 2, engine 1).
3. Elmer electrostatic / thermal artefact model (section 2, engine 2).
4. pyTDGL sheet-current model only if a published target formula is later
   opened.
5. Einstein Toolkit or GRChombo only if a concrete metric is proposed.

Stop rule: a result that depends on an unstated parameter (ion mobility, plasma
density, Cooper-pair density) is "parameter-limited," not evidence for or
against a claim. Promotion to `main` still needs two engines agreeing within
about 5%, a pull request, and James's approval. Installing any of these
engines still needs James's separate OK.

## 4. Operational notes

Raw Hermes material (prompt, draft, RESULT, job metadata and logs) is archived
privately and is not in this public repository.
