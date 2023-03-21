# ATAC-seq pipeline : From FASTQ to Peaks  

In this jupyter notebook, I show from scratch and end to end processing of ATAC-seq data. 
We start downloading a paired-end CTCF ATAC-seq experiment and focus on chromosome 22 region.
Then, we process the data, check quality of the paired reads, align reads to the reference genome (hg38) and call peaks. 
Finally, we visualize the peaks in genome browser. 

### Tools used:

    * FastQC
    * CutAdapt
    * Bowtie 2
    * SAMtools
    * Picard
    * BEDtools
    * MACS2

![Captura de tela de 2023-03-20 18-51-42](https://user-images.githubusercontent.com/101593641/226698491-42967121-c363-4a76-93dd-d3538a35d92c.png)



### References and data source 
This pipeline is based on the tutorial https://training.galaxyproject.org/training-material/topics/epigenetics/tutorials/atac-seq/tutorial.html#Green2012
and https://informatics.fas.harvard.edu/atac-seq-guidelines-old-version.html. 



