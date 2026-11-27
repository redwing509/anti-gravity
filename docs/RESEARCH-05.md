# RESEARCH-05 — Mach-effect (Woodward) thruster literature register (first slice)

`ag-research-05`, box job, 26 Nov 2026. Research documents only: no engine was installed or run, and this is not a propulsion-breakthrough claim.

Method: Hermes bite-size jobs (sources → verify → extract) on NVIDIA NIM Nemotron 3.5 Super VL (we-research, t1358u); every kept quote was then checked against the opened source (citation check 27 Nov 2026). Searches in English. Raw job files: [`RESEARCH-05-data/`](RESEARCH-05-data/).

Headline: in these four sources there is no matched independent confirmation of a Mach-effect force. TU Dresden attributes the observed signal to coupled vibrations on the torsion balance and saw no thrust in its SpaceDrive configurations; Fearn and Woodward themselves report the thrust disappearing in a balanced configuration. Positive force figures from the NIAC grant report are dropped as unconfirmed.


Four recorded URLs opened with curl. The arXiv record was read as HTML and the other three sources as complete PDFs. This slice supports reported nulls and conventional balance artifacts. Matched independent evidence of a new force was not found in these four sources.

- **S01 · Keep the authors’ null observation from the abstract.** “We find the thrust does indeed disappear in the experiment, as predicted.” This is the authors’ report about their own balanced configuration. Drop the positive thrust figure. [Fearn and Woodward, arXiv abstract](https://arxiv.org/abs/1301.6178)
- **S02 · Keep the independent artifact finding.** “It is concluded that the observed effect is a result of coupled vibrations on the torsion balance.” In §6 the authors report signals “in thruster orientations that should not result in thrust.” Drop the comparison of normalized force with absolute force and read the original EXTRACT’s combined sentence as separate excerpts. [TU Dresden proof](https://tu-dresden.de/ing/maschinenwesen/ilr/rfs/ressourcen/dateien/forschung/folder-2007-08-21-5231434330/ag_raumfahrtantriebe/ExperimentalInvestigationofMETsonTorsionBalances_Proof.pdf?lang=en)
- **S03 · Drop all positive force figures.** The reported figures can be located in the grant report, but this slice contains no matched independent confirmation. [NIAC final report](https://nasa.gov/wp-content/uploads/2018/03/niac_2018_phii_woodward_macheffects_2_tagged.pdf)
- **S04 · Keep the Mach-effect null.** “No thrusts were seen on any of these configurations.” The EXTRACT’s thermal-drift phrase completes the adjacent EMDrive discussion and is dropped as a Mach-effect attribution. [SpaceDrive, §6](https://tu-dresden.de/ing/maschinenwesen/ilr/rfs/ressourcen/dateien/forschung/folder-2007-08-21-5231434330/ag_raumfahrtantriebe/IAC-The-SpaceDrive-Project-Thrust-Balance-Development-and-New-Measurements-of-the-Mach-Effect-and-EMDrive-Thrusters.pdf?lang=en)
