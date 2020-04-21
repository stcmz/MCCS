# MCCS Samples

This repository stores the sample data for MCCS (Molecular Complex Characterization System).

1_original_gpcr_pdb_data
--------

This directory include a complete list of GPCR proteins from [GPCRdb](https://gpcrdb.org/structure/) that have known 3D structures determined by either [X-Ray crystallography](https://en.wikipedia.org/wiki/X-ray_crystallography) or [cryoEM technique](https://en.wikipedia.org/wiki/Cryogenic_electron_microscopy).

All are PDB files included were fetched from https://www.rcsb.org/ directly.

The list snapshot date is June 5, 2019.

2_manually_cleaned_up
--------

We then manually cleaned up the downloaded PDB files keeping only those have a non-peptide binding ligand and put them into this directory.

3_mccs_complete_output
--------

Finally [jdock](https://github.com/stcmz/jdock) was used to generate the per residue energy contribution, and another script was run for vector clustering and heatmap generation. The entire workspace including input/output/log is provided in this directory.