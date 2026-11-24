# RESEARCH-03 — EmDrive / closed microwave-cavity published tests (first bite-size literature slice, checked)

Date: 24 November 2026 (America/Los_Angeles).
This is the next Anti-Gravity rotation unit after RESEARCH-02 (James t1358u). It is a first bite-size literature slice of Roadmap Phase 2 item 2 (an EmDrive or closed microwave-cavity thermal and electromagnetic artifact check, including comparison to published null tests). Research documents only: no engine was installed or run, and no third-model build was started. Merging this document would not promote any model result. This is not a claim of a propulsion breakthrough or of a new gravitational force.

Hermes ran bite-size jobs on NVIDIA NIM Nemotron 3.5 Super VL. Every quote below was then checked against files the controller opened. Hermes first-pass wording that spliced sentences, used a journal phrasing not found in the opened conference PDF, or relied on a live page that could not be opened here is not used. No Sci-Hub, LibGen, or other pirate copy was used.

## Sources opened this pass

- Harold White, Paul March, James Lawrence, Jerry Vera, Andre Sylvester, David Brady, and Paul Bailey, *Measurement of Impulsive Thrust from a Closed Radio Frequency Cavity in Vacuum*, official NASA NTRS PDF `20170000277.pdf`, opened as full text (HTTP 200). https://ntrs.nasa.gov/api/citations/20170000277/downloads/20170000277.pdf The authors are listed on the opened PDF as being at NASA Johnson Space Center.
- M. Tajmar, O. Neunzig, and M. Weikert, *High-Accuracy Thrust Measurements of the EMDrive and Elimination of False-Positive Effects*, Space Propulsion 2020+1 conference paper SP2020_268, 17–19 March 2021, official PDF hosted by TU Dresden, opened as full text (HTTP 200). https://tu-dresden.de/ing/maschinenwesen/ilr/rfs/ressourcen/dateien/forschung/folder-2007-08-21-5231434330/ag_raumfahrtantriebe/SPC-High-Accuracy-Thrust-Measurements-of-the-EMDrive-and-Elimination-of-False-Positive-Effects.pdf The live Springer page for the later CEAS Space Journal article (DOI 10.1007/s12567-021-00385-1) returned a bot-check page here and was not used for quotes.
- *Anomalous Thrust Production from an RF Test Device Measured on a Low-Thrust Torsion Pendulum*, official NASA NTRS citation record 20140006052. The live NTRS URL did not complete in this environment. The official abstract was opened from the Internet Archive snapshot of that same URL (2026-11-02). https://ntrs.nasa.gov/citations/20140006052 · archive: https://web.archive.org/web/20261102025427id_/https://ntrs.nasa.gov/citations/20140006052 Opened as abstract only. The snapshot lists a public PDF; that PDF was not successfully fetched here.

## What the opened literature actually says

### NASA Eagleworks vacuum campaign (White et al., official NTRS PDF)

The opened PDF reports a vacuum test of a tapered RF cavity. Abstract wording (line breaks joined): “A vacuum test campaign evaluating the impulsive thrust performance of a tapered RF test article excited in the TM212 mode at 1,937 megahertz (MHz) has been completed. The test campaign consisted of a forward thrust phase and reverse thrust phase at less than 8 × 10−6 Torr vacuum with power scans at 40 watts, 60 watts, and 80 watts. The test campaign included a null thrust test effort to identify any mundane sources of impulsive thrust, however none were identified. Thrust data from forward, reverse, and null suggests that the system is consistently performing with a thrust to power ratio of 1.2 ± 0.1 mN/kW.”

Geometry, as printed: “The RF resonance test article is a copper frustum with an inner diameter of 27.9 cm on the big end, inner diameter of 15.9 cm on the small end, and an axial length of 22.9 cm.” “The test article contains a 5.4 cm-thick disc of polyethylene with an outer diameter of 15.6 cm that is mounted to the inside face of the smaller diameter end of the frustum.” “A 13.5 millimeter diameter loop antenna drives the system in the TM212 mode at 1,937 MHz.”

Facilities wording (line breaks and a layout exponent joined): “Vacuum conditions are provided by two roughing pumps and two high-speed turbo pumps, and all vacuum tests were performed at or below 8×10−6 Torr.” On the null-mount tests: “The results from the null thrust testing show no impulsive element in the collected data, only the thermal signal.” The same PDF also states “a null thrust test effort of three tests performed at vacuum at 80 W.”

This is a published official NASA report of a measured thrust-to-power ratio, plus the authors’ own null-mount result. It is not an independent replication, and it is not a model result from this project.

### TU Dresden conference null test (Tajmar, Neunzig, and Weikert, official conference PDF)

The opened official file is the Space Propulsion 2020+1 conference paper (SP2020_268), not the later journal article. Abstract wording (column line breaks joined): “Using a geometry and operating conditions close to the model by White et al that reported positive results published in the peer-reviewed literature, we found no thrust values within a wide frequency band including several resonance frequencies. Our data limits any anomalous thrust to below the force equivalent from classical radiation for a given amount of power. This provides strong limits to all proposed theories and rules out previous test results by more than three orders of magnitude.”

Geometry, as printed: “Our cavity is based on the same geometry as the one used by White et al [3] to compare with peer-reviewed results. It consists of a tapered cone, which was mechanically pressed, with a cylindrical flange and a collar made out of 2 mm thick copper as shown in Fig. 7.” The paper also gives a “resonant frequency of 1,914 MHz, which was close to the 1,937 MHz used by White et al [3],” and “an unloaded Qu factor of approximately 23,000.”

A first-pass Hermes quote that said previous results were ruled out “by at least two orders of magnitude,” and that used “2 mm-thick copper,” was not used. Those wordings were not taken from this opened conference PDF.

This is a published official university conference paper reporting a null / photon-thrust-limit result. It is not a simulation by this project.

### NASA 2014 NTRS abstract (ambient-pressure campaign)

From the opened official abstract on the archived NTRS page: “Approximately 30-50 micro-Newtons of thrust were recorded from an electric propulsion test article consisting primarily of a radio frequency (RF) resonant cavity excited at approximately 935 megahertz. Testing was performed on a low-thrust torsion pendulum that is capable of detecting force at a single-digit micronewton level, within a stainless steel vacuum chamber with the door closed but at ambient atmospheric pressure.” “The torsion pendulum was designed, built, and operated by Eagleworks Laboratories at the NASA Johnson Space Center of Houston, Texas.” “Thrust was observed on both test articles, even though one of the test articles was designed with the expectation that it would not produce thrust. Specifically, one test article contained internal physical modifications that were designed to produce thrust, while the other did not (with the latter being referred to as the “null” test article).”

This record is abstract only in this slice. The full conference PDF was not opened. The abstract itself reports thrust on a “null” test article and that the chamber was at ambient pressure with the door closed, so it is not a vacuum-thrust measurement.

## Ratings (this slice only)

- **Document, do not promote as a project result:** White et al. official NASA PDF — published geometry (copper frustum 27.9 / 15.9 cm inner diameters, 22.9 cm axial length, polyethylene disc, TM212 at 1,937 MHz) and a reported 1.2 ± 0.1 mN/kW vacuum campaign, with a null-mount test the authors say showed only a thermal signal. Useful later for an approved-solver comparison; not validated here.
- **Document as a published null / upper-limit result:** Tajmar, Neunzig, and Weikert official TU Dresden conference PDF — White-like tapered copper cavity, 1,914 MHz, unloaded Qu about 23,000; no thrust found in the reported frequency band; authors limit any anomalous thrust to below classical radiation and say this rules out previous test results by more than three orders of magnitude. The CEAS journal version was not opened.
- **Document with limits:** 2014 NTRS abstract — ~30–50 µN at ~935 MHz, ambient pressure, thrust also reported on a “null” test article. Full PDF not opened.

No engine install, solver run, or “breakthrough” claim follows from this slice.

## Gaps to carry forward

- The CEAS Space Journal article (DOI 10.1007/s12567-021-00385-1) was not opened (Springer bot-check). Quotes are from the official TU Dresden conference PDF of the same title, which may differ from the journal text.
- The 2014 NTRS full PDF (`20140006052.pdf`) was listed on the archived citation page but was not successfully fetched. That campaign remains abstract only.
- No other official null tests, thermal-artifact papers, or cavity-geometry drawings were opened in this first slice.
- Modeling with an independent EM solver still needs an approved engine (Roadmap Phase 1) and was not started.

NOT FOUND in this slice: an opened official copy of the CEAS journal article; an opened full text of NTRS 20140006052; any simulation by this project.

## Relation to the roadmap

RESEARCH-01 surveyed engines and literature. RESEARCH-02 was the EHD / ionic-wind literature register (Phase 2 item 1). This file starts Phase 2 item 2 as a literature register only. Phase 1 engine approval is still required before any model-only study. Remaining Covid unit 2 sub-units are not part of this document.

## Hermes status

Bite-size jobs ran on the box under the t1358u we-research profile (NVIDIA NIM `nvidia/nemotron-3.5-super-vl-120b-a12b`). Sources finished at 12:40 PM PST on 24 Nov 2026, rc 0; verifies ran from 12:43 to 12:59 PM PST (S02 first attempt exited 130 and was retried, then rc 0); extract finished at 1:06 PM PST, rc 0. The controller opened the official NASA White et al. PDF, the official TU Dresden conference PDF, and the archived NTRS 2014 abstract, and checked each quote before this note was written. Supporting job files are in `docs/RESEARCH-03-data/`.
