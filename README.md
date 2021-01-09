# DNA-Skew-GUI
Made a small Project for uni Bioinformatics. Used to evaluate software design principles and concepts (DFGs etc...) First time using Pyhton based GUI (tkinter):

Will segment each geneseq and decode the protien and Calculate the NC value for that gene. Also plots the GC-Skew for the whole genome. Needs the full genome data and the segmented gene data. For now, the gene data must be segmented in the way given in GeneSeq.txt due to how I coded the Regex for the extraction.

To run:
  If on windows or linux just double click it or use the shell/cmd and type python3 DnaPlot.py
  Should work the same way on a mac untested.
  
Use full screen. Some buttons are hidden when first opened.
For the first text input the input should just contain the name and no extension. It expects a .txt to be present in the pwd and should be in the format as given in GeneSeq.txt. Most dna genome seq data can be found in that form online.

It will segment the gene sequence and decode it into the corresponding protiens. While catching any common errors. Would also calculate the Nc value for that particular gene.

For the second input it expects a full genome data sequence in txt format. It will print the GC and AT skew graphs.

Ofcourse this is really just glued together and can be much much better in a lot of ways but for now I am working on something else so probably would stay the same. Feel free to fork out much better version or even better just use biopython :P
