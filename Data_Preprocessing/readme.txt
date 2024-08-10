<h1 align="center">Data Preprocessing Techniques</h1>

1. may3fullnotnormalized.csv : contains the raw data captured through the experimentations with the amino acid samples in the ED spectrometer. It is important to note that this file was made by merging the individual files captured on different dates. The column "files" in this CSV states the dates on which data (each row) has been captured.
2. 1_ED_paper_amino_AI_baselinecorrection.ipynb : It contains the codes processing may3fullnotnormalized.csv. The data is baseline corrected as explained in the paper to create may3fullbaselinelinearnotnormalized.csv.
3. 2_ED_paper_amino_AI_normalizationafterbaselineremoval.ipynb : It contains the codes processing may3fullbaselinelinearnotnormalized.csv. The data is normalized as explained in the paper to create may3fullbaselinlinearnormalized.csv.
4. 3_ED_paper_amino_AI_correlationrankedandelimination.ipynb : It contains the codes processing may3fullbaselinlinearnormalized.csv. The data is analyzed for correlations and some rows are eliminated based on the correlation values as explained in the paper to create may3fulllinearrankedfiltered.csv.
