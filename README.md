# polkadot
Polka dot plot code for analysis of Chandra or XMM observed x-ray emission from massive stars' stellar winds.
Please note the markdown cell at the top of the code, providing instructions for proper use.
With .txt and .dat files installed to the same folder as the code, it should 'run all' properly with the test data.

FILES INCLUDED <br>
PolkaDot_Plot.ipynb - code for producing polka dot plots as well as basic spectra <br>
TESTdat.dat - sample data to ensure the code is running properly <br>
zpup_lines_chandra.txt and zpup_lines_xmm - text files containing information on emission lines. Follows structure: <br>
&emsp;column 1 - line names <br>
&emsp;column 2 - line central wavelength (Angstroms) <br>
&emsp;column 3 - line temperatures (Kelvin) <br>
&emsp;columns 4 & 5 - MEG/RGS1 emission boundaries <br>
&emsp;columns 6 & 7 - MEG/RGS1 continuum boundaries <br>
&emsp;columns 8 & 9 - HEG/RGS2 emission boundaries <br>
&emsp;columns 10 & 11 - HEG/RGS2 continuum boundaries <br>
zpup_lines_master.txt - master list of lines present in zpup's spectra. Many of these blend together, so we don't make dots for all of them. This file is for book-keeping only; it is not used in the code.