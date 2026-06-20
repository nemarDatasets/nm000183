[![DOI](https://img.shields.io/badge/DOI-10.82901%2Fnemar.nm000183-blue)](https://doi.org/10.82901/nemar.nm000183)

Multicenter iEEG dataset for classification of graphoelements and artifactual signals (FNUSA)

Official iEEG-BIDS release (MEF3) by Nejedly et al. 2020, Scientific Data
(doi:10.1038/s41597-020-0532-5; data doi:10.6084/m9.figshare.12191868), with metadata enrichment. Recording
data are unchanged; only sidecars, electrodes.tsv, participants.tsv and this
README were added or corrected. See papers/Nejedly2020_SciData_MAYO_FNUSA.md.

Recording (from the paper)
  - Institution: St. Anne's University Hospital, Brno, Czech Republic (FNUSA)
  - Acquisition: M&I, BrainScope BrainScope, 25 kHz original ->
    downsampled to 5 kHz. Power line: 50 Hz. Ground: n/a.
  - 30 min awake resting interictal recording.

Electrodes (from the paper)
  - Standard intracranial depth electrodes (5/10/15-contact semi-flexible, ALCIS, Platinum); 2 mm contact length, 0.8 mm diameter, 1.5 mm inter-contact spacing.
  - electrodes.tsv lists every contact with shaft group, SOZ flag and (where
    available) anatomy. Coordinates are n/a: patient positions were never published.

Channels labelled in description as soz / nonsoz indicate the seizure onset zone.
