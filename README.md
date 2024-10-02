Calculate the gene activate score and peak gene regulatory score by MAESTRO.

Calculate gene active score 
Input: peak_count_matrix: a peak_count matrix from scATAC-seq with peak * cell; organism: species type human: GRCh38 / mouse: GRCm38 
Output: a gene * cell matrix, the elements represent the gene activity for the cell
Calculate peak-gene regulatory score 
Input: peak_count_matrix: a peak_count matrix from scATAC-seq with peak \* cell organism: species type human: GRCh38 / mouse: GRCm38 
Output: a gene * peak matrix, the elements represent the regulatory potential for peak to gene
