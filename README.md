# FWI
Acoustic Full-waveform inversion (FWI) for isotropic media in time domain.\
Acoustic wave equation is solved with fixed boundary condition. Forward and adjoint wavefields are cross-correlated to calculate the gradient for velocity correction.

# Generate true recordings
Run 'generate_true_rec.m' to generate true recordings 'true_rec.mat' based on a toy model 'trueModel'. Below is our true velocity model (stolen from the courst TPG4155 at NTNU).
![true velocity](https://user-images.githubusercontent.com/45905048/68906553-f81c5b80-0744-11ea-90ab-1384d10d7f28.jpg)
# Run FWI with true recordings
Run 'FWI,mat' to process FWI based on the true recordings to reconstruct the velocity model. The starting model is given below.
![starting velocity](https://user-images.githubusercontent.com/45905048/68906711-855fb000-0745-11ea-812b-d576b0eb66ec.jpg)
Below is the result after 60 times of interations.
![progress](https://user-images.githubusercontent.com/45905048/68906398-66145300-0744-11ea-85ae-a0602992f461.jpg)