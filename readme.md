## README

Data analysis in support of "Reduced enteric BDNF-Trkb signaling drives glucocorticoid-mediated GI dysmotility", Slosberg, J. & Puttapaka, S., et al

These data represent the changing transcriptional profiles of the longitudinal muscle and myenteric plexus (LMMP) of the murine ileum with age. Tissues from 1-month, 6-month, and 17-month old mice were characterized. 

Raw and processed (pseudoalignment via Kallisto) data are available on NCBI GEO: GSE284108

### Gene-level differential expression (diffexp.Rmd)
  - DESeq2: expression ~ age + RIN + batch, Wald-test
  
###Isoform splicing analysis: ./isoform_level_analysis
  - DEXSeq (isoformSwitchAnalyzeR wrapper)


