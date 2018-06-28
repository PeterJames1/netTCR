# netTCR
predicting peptide and TCR interaction

`python scripts/netTCR.py -infile test_data/data.txt -outfile NetTCR_predictions.txt`

or with TCR list and peptide spcification:

`python scripts/netTCR.py -infile test_data/data_tcr_list.txt -peptides GLCTLVAML,NLVPMVATV -outfile NetTCR_predictions.txt`

the options for peptides should be:

GLCTLVAML, NLVPMVATV and GILGFVFTL
