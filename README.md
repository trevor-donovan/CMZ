Both analysis codes assume a csv input as produced by a certain post-processing code which processes data from CERN's Tpx3Cam. Each csv is read in as a pandas dataset, 
rows of which represent detections of single photons.

The file titled GaAs_realign_cent is meant for analyzing an Ar lamp input which has a discrete number of singlet/doublet spots, and the other one is for spectrally continuous light.