# Project3_Python
Scientific Question:
Which is the better model species, Mus musculus (house mouse) or Pan troglodytes (chimpanzee), for testing asthma caused by the interleukin-13 gene in humans?

To run the adequately run the code you need to download 3 files:

1) IL13_Human (1).fasta
2) IL13_Mouse (1).fasta
3) IL13_Chimpanzee (1).fasta

Information about where FASTA files were found:
  The data on the IL-13 gene can be obtained from the UniProt database (https://www.uniprot.org/).  The gene sequence for the IL-13 protein is taken from https://www.uniprot.org/uniprot/P35225 (for humans also called Homo sapiens), https://www.uniprot.org/uniprot/P20109 (for mice also called Mus musculus), https://www.uniprot.org/uniprot/P61126(for chimpanzees also called Pan troglodytes). The UniProt database already has the gene in FASTA format. Simply search the gene of interest and within the page, use ctrl+F and type in FASTA to find the download link. Click on it and copy all the information in the pop-up window. Then go to Jupyter notebook, open a new text file and paste in the information from the FASTA link, label the file as IL13_Human(Chimpanzee or Mouse).fasta.
  The output was two pairwise sequence alignments and dotplots of the human sequence compared to both the mouse and chimpanzee sequences for the interleukin-13 gene.
