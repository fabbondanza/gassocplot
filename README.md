# gassocplot
Regional association plots for genetic and epigenetic data.

# Functions
* assoc_plot - plots a regional association plot for a single trait within a genomic region.  
* stack_assoc_plot - plots a stacked regional association plot for multiple traits within a genomic region.  

# Installation
1. install.packages("devtools")
2. library(devtools) 
3. install_github("jrs95/gassocplot")
4. library(lmrse)

# Example
\#\#\# assoc_plot  
markers <- gassocplot::test_assoc_plot  
head(markers)  
corr <- gassocplot::test_assoc_plot_corr   
assoc_plot(markers, corr)   

\#\#\# stack_assoc_plot  
markers <- gassocplot::test_stack_assoc_plot_markers  
head(markers)  
corr <- gassocplot::test_corr   
assoc_plot(markers, corr)   
