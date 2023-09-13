# Statistical analysis and visualization of transcriptomic and proteomic data for *Ruegeria pomeroyi* DSS-3 and *Alteromonas macleodii* MIT1002

This repo contains a jupyter notebook (Python 3.7.8) assembled for the purpose of analyzing metabolic expression data from the marine bacteria *Ruegeria pomeroyi* DSS-3 and *Alteromonas macleodii* MIT1002.
Transcriptomic (mRNA) and proteomic expression data are included in the `./data/` folder. This data is listed as gene coverages, showing abundance of that data type for each gene for each strain.
Gene calling and annotation were done for each strain using Anvi'o.

Experimental setup:
Each strain was grown in a marine basal medium with defined carbon substrates at 12 mM carbon equivalent total of either acetate, glucose, or a 2:1 mixture of both.
Samples were taken in exponential phase for the glucose and acetate-only cultures.
For mixed substrate cultures, *R. pomeroyi* DSS-3 had 4 mM acetate and 8 mM glucose and *A. macleodii* MIT1002 had 4 mM glucose and 8 mM acetate. 
Each of these cultures was sampled in "early" (before depletion of the limited substrate) or "late" (after depletion of the limited substrate) exponential phase.

These comparisons were designed to investigate how these bacteria alter their metabolic expression to match the available substrates.

More detailed notes on the analyses are included in the jupyter notebook.
