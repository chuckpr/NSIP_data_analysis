# This is the data analysis repo for our soil crust Nitrogen-SIP manuscript

>**Charles Pepe-Ranney**, Chantal Koechli, Ruth Potrafka, Cheryl Andam, Erin
>Eggleston, Ferran Garcia-Pichel, Daniel H Buckley. Non-cyanobacterial
>diazotrophs dominate dinitrogen fixation in biological
>soil crusts during early crust formation. 

A preprint can be found at
[http://dx.doi.org/10.1101/013813](http://dx.doi.org/10.1101/013813).  

## IPython notebooks for each figure

[Figure 1](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/figures_and_stats/ordination_heavy_fractions.ipynb)  
[Figure 2](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/figures_and_stats/l2fc.ipynb)  
[Figure 3](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/figures_and_stats/trees.ipynb)  
[Figure 4](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/figures_and_stats/scatter_top10.ipynb)  

## IPython notebooks for supplemental figures

[Figure S1](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/figures_and_stats/ordination_all.ipynb)  
[Figure S2](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/figures_and_stats/interaction.ipynb)  
[Figure S3]()  
[Figure S4](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/figures_and_stats/rarefaction_curves.ipynb)  
[Figure S5](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/figures_and_stats/diazotroph_distribution.ipynb)  

## Sequence processing IPython notebooks

[Quality control of DNA-SIP 16S rRNA gene sequences](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/QC.ipynb)  
[Download Garcia-Pichel data](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/download_Garcia-Pichel_2013.ipynb)  
[Download Steven 2013 data](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/download_steven_2013_data.ipynb)  
[Merge datasets](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/merge_datasets.ipynb)  
[Merge metadata from each dataset](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/merge_metadata.ipynb)  
[Taxonomically annotate 16S sequences](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/assign_taxonomy.ipynb)  
[Bin 16S sequences into OTUs](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/OTU_binning.ipynb)  
[BLAST sequences against LTP database](http://nbviewer.ipython.org/github/chuckpr/NSIP_data_analysis/blob/master/BLAST.ipynb)  

## Description of files in data directory

| Filename | Description |
| ------------------------------------------ | ------------------------------------------------------------------------|
| LTP_blast_table.tsv                        | BLAST hits against LTP database for OTU centroids |
| barcode_mapper.txt                         | barcodes and sample information for DNA-SIP 16S rRNA gene sequences     |
| finalQC.fasta.bz2                          | All 16S rRNA sequences after quality control |
| garciapichel2013.csv                       | Sample information for Garcia-Pichel data |
| OTU_table_wtax.biom                        | OTU table with taxonomic annotations |
| otusn_yeager2006.fasta                     | OTU centroid sequences |
| sample_data_combined_qiime_format.tsv      | QIIME formatted sample data table for combined datasets |

