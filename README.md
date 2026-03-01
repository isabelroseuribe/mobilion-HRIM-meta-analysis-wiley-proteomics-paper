# mobilion-HRIM-meta-analysis-wiley-proteomics-paper
R scripts to create Human peptide library and then subset the library to pull out co-eluting, co-isolated isobars in different simulated instrument modes. The peptide library can be accessed here: https://analyticalsciencejournals.onlinelibrary.wiley.com/doi/10.1002/pmic.70084. 

250214_create_peptide_library: script to join the results of the pre-trained learning models PeptDeep and DeepCollisionalCrossSection (accessible in Supplemental Data 1 from https://www.nature.com/articles/s41467-021-21352-8).

250331_quad_filtering: script to pull out chimeric precursor groups from different quadrupole isolation windows.

250331_hrim_filtering: script to pull out chimeric precursor groups from different ion mobility isolation windows.

250331_quad-hrim_filtering: script to pull out chimeric precursor groups from different combinations of quadrupole and ion mobility isolation windows.

250331_filtering_analysis: script to visualize properties of the peptide library for figure 2 and the properties of chimeric precursor groups for figure 3A-F.
