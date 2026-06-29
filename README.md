Nejedly2020 multicenter iEEG graphoelement clips (FNUSA)

This BIDS dataset is converted from the public segmented .mat archives released
with Nejedly et al. 2020, Scientific Data:
https://doi.org/10.1038/s41597-020-0532-5

The source data are independent 3 s single-channel iEEG clips. The original
authors also released MEF3 BIDS archives for reviewer-requested compatibility,
but those contain the same data as the .mat clips. This conversion therefore
uses the segmented archives directly.

Layout
------
Each BIDS run contains clips from one subject and one source SEEG contact,
concatenated at 5000 Hz. Events mark the 3 s clip boundaries and preserve the
original label, segment_id, anatomy, reviewer_id, SOZ flag, and electrode type.
The runs are not continuous clinical recordings and should not be interpreted as
real time-contiguous data across clip boundaries.

Subject labels preserve the original NEMAR/OpenNeuro style (for example sub-000) because this is a single-site dataset.

Electrodes
----------
Patient-specific electrode coordinates were not released with the segmented
dataset. Therefore electrodes.tsv keeps x/y/z as n/a while preserving contact
names, material, and manufacturer. Anatomy and SOZ labels are preserved per clip
in events.tsv.
