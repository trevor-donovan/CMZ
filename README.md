Both analysis codes assume a csv input as produced by a certain post-processing code which processes data from CERN's Tpx3Cam. Each csv is read in as a pandas dataframe, 
rows of which represent detections of single photons.

The file titled GaAs_realign_cent is meant for analyzing an Ar lamp input which has a discrete number of singlet/doublet spots. It's a slightly older and more awkward code than the other GaAs_Ar1s code, but it has better results to show because it was taken over a longer time. I recommend basing any further discrete-wavelength code on the Ar1s.

The shape-finding code is an in-progress attempt (it doesn't work right yet) to find how horizontal the spectrum is on the pixel array.
