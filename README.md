The prs software package incorporates functions to generate pseudorandom binary and ternary signals. Six classes of signals are available:\
•	Maximum length binary (MLB) signals \
•	Quadratic residue binary (QRB) signals \
•	Quadratic residue ternary (QRT) signals \
•	Hall binary (HAB) signals \
•	Twin Prime binary (TPB) signals \
•	Direct synthesis ternary signals (through a subsidiary program)

Functions are also available to calculate three measures of signal quality:\
•	Performance Index for Perturbation Signals (PIPS) \
•	Effective Performance Index for Perturbation Signals (PIPSE) \
•	Effective minimum ratio between the actual harmonic amplitude and the specified harmonic amplitude at any of the specified harmonics (EMINE) 

To run the prs package, download prs.zip and unzip the file. Change the "Current Directory" in MATLAB to the location of the folder. The GUI is then run by typing "prs" in the MATLAB command window. The use of the GUI requires MATLAB version 6.5 or above. However, for lower versions of MATLAB, the program can be run by typing "prs_perturbation" in the MATLAB command window; user input is mainly through the keyboard. Expert users can, of course, make use of the separate functions without calling the main script files "prs" or "prs_perturbation".

Citation requests:\
•	Tan, A. H. and Godfrey, K. R.: ‘The generation of binary and near-binary pseudorandom signals: an overview’, IEEE Transactions on Instrumentation and Measurement, 2002, 51, (4), pp. 583 – 588.\
•	Tan, A. H. and Godfrey, K. R.: Industrial Process Identification: Perturbation Signal Design and Applications. Cham, Switzerland: Springer, 2019. 

The prs package has a subsidiary program which allows the user to generate direct synthesis ternary signals. The direct synthesis signals are based on the five classes of signals from the main program (MLB, QRB, QRT, HAB and TPB). The subsidiary program can be run by typing "direct_synthesis" in the MATLAB command window. 

Citation requests for direct synthesis ternary signals:\
•	Tan, A. H.: ‘Direct synthesis of pseudo-random ternary perturbation signals with harmonic multiples of two and three suppressed’, Automatica, 2013, 49, (10), pp. 2975 – 2981.\
•	Tan, A. H. and Godfrey, K. R.: Industrial Process Identification: Perturbation Signal Design and Applications. Cham, Switzerland: Springer, 2019. 
