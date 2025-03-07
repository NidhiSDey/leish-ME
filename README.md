# Project leish-ME: IDO1/PD-L1 in infected microenvironments


# IL-32 producing CD8+ memory T cells and Tregs define the IDO1/PD-L1 niche in human cutaneous leishmaniasis skin lesions.

### Nidhi S. Dey<sup>1</sup>, Shoumit Dey<sup>1</sup>, Naj Brown<sup>1</sup>, Sujai Senarathne<sup>2</sup>, Luiza Campos Reis<sup>3,¥</sup>, Ritika Sengupta<sup>4</sup>, Jose Angelo L. Lindoso<sup>5,6</sup>, Sally James<sup>5</sup>, Lesley Gilbert<sup>5</sup>, Mitali Chatterjee<sup>4</sup>, Hiro Goto<sup>3</sup>, Shalindra Ranasinghe<sup>2</sup> and Paul M. Kaye<sup>1*</sup>

<sup>1</sup>York Biomedical Research Institute and Skin Research Centre, Hull York Medical School, University of York, UK.
<sup>2</sup>Department of Parasitology, Faculty of Medical Sciences, University of Sri Jayewardenepura, Sri Lanka.
<sup>3</sup>Department of Preventive Medicine, Instituto de Medicina Tropical de São Paulo, Faculdade de Medicina, Universidade de São Paulo, Brazil.
<sup>4</sup>Department of Pharmacology, Institute of Postgraduate Medical Education and Research, Kolkata, India. 
<sup>5</sup>Secretaria de Saúde do Estado de São Paulo, Instituto de Infectologia Emílio Ribas, São Paulo, SP, Brasil 
<sup>6</sup>University of São Paulo, Faculty of Medicine, Department of Infectious and Parasitic Diseases, São Paulo, SP, Brazil.
<sup>7</sup>Technology Facility, Department of Biology, University of York, York, YO10 5DD

<sup>*</sup>Correspondence:  Paul M. Kaye, paul.kaye@york.ac.uk
<sup>¥</sup> Current address: Escuela Profesional de Medicina Humana, Facultad de Medicina, Universidad Nacional Toribio Rodríguez de Mendoza de Amazonas, Chachapoyas, Peru.

Key words: Human cutaneous leishmaniasis, Host directed therapy, skin, IL-32, CD8 memory T cells, Regulatory T cells, Prognosis, Spatial Transcriptomics, IDO1, PD-L1, myeloid cells.

# Abstract

Human cutaneous leishmaniasis (CL) is characterised by chronic skin pathology.  Experimental and clinical data suggest that immune checkpoints (ICs) play a crucial role in disease outcome but the cellular and molecular niches that facilitate IC expression during leishmaniasis are ill-defined.   We previously showed that in Sri Lankan patients with CL two ICs, indoleamine 2,3-dioxygenase 1 (IDO1) and programmed death-ligand 1 (PD-L1) are enriched in lesional skin and that reduced PD-L1 expression early after treatment onset predicts cure rate following antimonial therapy.  Here, we use spatial cell interaction mapping to identify IL-32-expressing CD8+ memory cells and regulatory T cells as key components of the IDO1 / PD-L1 niche in a cohort of Sri Lankan CL patients.  This finding was confirmed in patients with distinct forms of dermal leishmaniasis in Brazil and India.  Furthermore, in our Sri Lankan cohort the abundance of IL-32+ cells and IL-32+CD8+ T cells at treatment onset was prognostic for rate of cure.  This study provides a unique spatial perspective on the expression of key ICs in these important skin diseases and a novel route to identify biomarkers of treatment response.  


## Software requirements: 

### OS: Tested on
1. Windows 11
2. Ubuntu 22.04.03 LTS

#### Suggested computing requirements: 
1. Processor 3 GHz and above
2. RAM above 32GB

#### Software
1. R version 4.1.2 (2021-11-01) and RStudio 2023.09.1 
2. Packages and versions needed for all Visium based analysis
> sessionInfo()
R version 4.1.2 (2021-11-01)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Ubuntu 22.04.3 LTS

Matrix products: default
BLAS:   /usr/lib/x86_64-linux-gnu/blas/libblas.so.3.10.0
LAPACK: /usr/lib/x86_64-linux-gnu/lapack/liblapack.so.3.10.0

locale:
 [1] LC_CTYPE=en_GB.UTF-8       LC_NUMERIC=C               LC_TIME=en_GB.UTF-8        LC_COLLATE=en_GB.UTF-8     LC_MONETARY=en_GB.UTF-8   
 [6] LC_MESSAGES=en_GB.UTF-8    LC_PAPER=en_GB.UTF-8       LC_NAME=C                  LC_ADDRESS=C               LC_TELEPHONE=C            
[11] LC_MEASUREMENT=en_GB.UTF-8 LC_IDENTIFICATION=C       

attached base packages:
[1] grid      stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] reshape2_1.4.4         VennDiagram_1.7.3      futile.logger_1.4.3    stringr_1.5.0          corrplot_0.92          gplots_3.1.3          
 [7] spatstat_3.0-7         spatstat.linnet_3.1-3  spatstat.model_3.2-8   rpart_4.1.16           spatstat.explore_3.2-5 nlme_3.1-155          
[13] spatstat.random_3.2-1  spatstat.geom_3.2-7    spatstat.data_3.0-3    ggpubr_0.6.0           RColorBrewer_1.1-3     patchwork_1.1.3       
[19] ggplot2_3.4.4          sqldf_0.4-11           RSQLite_2.3.2          gsubfn_0.7             proto_1.0.0            dplyr_1.1.3           
[25] SeuratObject_5.0.0     Seurat_4.4.0          

loaded via a namespace (and not attached):
  [1] backports_1.4.1       spam_2.10-0           plyr_1.8.9            igraph_1.5.1          lazyeval_0.2.2        sp_2.1-1             
  [7] splines_4.1.2         listenv_0.9.0         scattermore_1.2       digest_0.6.33         htmltools_0.5.6.1     fansi_1.0.5          
 [13] magrittr_2.0.3        memoise_2.0.1         tensor_1.5            cluster_2.1.2         ROCR_1.0-11           limma_3.50.3         
 [19] globals_0.16.2        matrixStats_1.0.0     spatstat.sparse_3.0-3 colorspace_2.1-0      blob_1.2.4            ggrepel_0.9.4        
 [25] xfun_0.41             crayon_1.5.2          tcltk_4.1.2           jsonlite_1.8.7        progressr_0.14.0      survival_3.2-13      
 [31] zoo_1.8-12            glue_1.6.2            polyclip_1.10-6       gtable_0.3.4          leiden_0.4.3          car_3.1-2            
 [37] future.apply_1.11.0   abind_1.4-5           scales_1.2.1          futile.options_1.0.1  DBI_1.1.3             rstatix_0.7.2        
 [43] miniUI_0.1.1.1        Rcpp_1.0.11           viridisLite_0.4.2     xtable_1.8-4          reticulate_1.34.0     bit_4.0.5            
 [49] dotCall64_1.1-0       htmlwidgets_1.6.2     httr_1.4.7            ellipsis_0.3.2        ica_1.0-3             farver_2.1.1         
 [55] pkgconfig_2.0.3       uwot_0.1.16           deldir_1.0-9          utf8_1.2.4            labeling_0.4.3        tidyselect_1.2.0     
 [61] rlang_1.1.1           later_1.3.1           munsell_0.5.0         tools_4.1.2           cachem_1.0.8          cli_3.6.1            
 [67] generics_0.1.3        broom_1.0.5           ggridges_0.5.4        evaluate_0.23         fastmap_1.1.1         yaml_2.3.7           
 [73] goftest_1.2-3         knitr_1.45            bit64_4.0.5           fitdistrplus_1.1-11   caTools_1.18.2        purrr_1.0.2          
 [79] RANN_2.6.1            pbapply_1.7-2         future_1.33.0         mime_0.12             formatR_1.14          compiler_4.1.2       
 [85] rstudioapi_0.15.0     plotly_4.10.3         png_0.1-8             ggsignif_0.6.4        spatstat.utils_3.0-4  tibble_3.2.1         
 [91] stringi_1.7.12        lattice_0.20-45       Matrix_1.6-1.1        vctrs_0.6.4           pillar_1.9.0          lifecycle_1.0.3      
 [97] lmtest_0.9-40         RcppAnnoy_0.0.21      data.table_1.14.8     cowplot_1.1.1         bitops_1.0-7          irlba_2.3.5.1        
[103] httpuv_1.6.12         R6_2.5.1              promises_1.2.1        KernSmooth_2.23-20    gridExtra_2.3         parallelly_1.36.0    
[109] codetools_0.2-18      lambda.r_1.2.4        MASS_7.3-55           gtools_3.9.4          chron_2.3-61          withr_2.5.2          
[115] sctransform_0.4.1     mgcv_1.8-39           parallel_4.1.2        tidyr_1.3.0           rmarkdown_2.25        carData_3.0-5        
[121] Rtsne_0.16            shiny_1.7.5.1   

3. Giotto - Requires specific commit installation: Please use the following link to run directly on R; depends on the remotes library: remotes::install_github("RubD/Giotto@0c8c2866e881b1c6b35ddc97c24dcb58b555c375")
4. Packages and versions required for CoxMx analysis
> sessionInfo()
R version 4.1.2 (2021-11-01)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Ubuntu 22.04.3 LTS

Matrix products: default
BLAS:   /usr/lib/x86_64-linux-gnu/blas/libblas.so.3.10.0
LAPACK: /usr/lib/x86_64-linux-gnu/lapack/liblapack.so.3.10.0

locale:
 [1] LC_CTYPE=en_GB.UTF-8       LC_NUMERIC=C               LC_TIME=en_GB.UTF-8        LC_COLLATE=en_GB.UTF-8     LC_MONETARY=en_GB.UTF-8   
 [6] LC_MESSAGES=en_GB.UTF-8    LC_PAPER=en_GB.UTF-8       LC_NAME=C                  LC_ADDRESS=C               LC_TELEPHONE=C            
[11] LC_MEASUREMENT=en_GB.UTF-8 LC_IDENTIFICATION=C       

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
[1] Giotto_2.0.0.9021 ggplot2_3.4.4     reticulate_1.34.0 rcartocolor_2.1.1 dplyr_1.1.3       remotes_2.4.2.1  

loaded via a namespace (and not attached):
 [1] Rcpp_1.0.11       rstudioapi_0.15.0 knitr_1.45        magrittr_2.0.3    rappdirs_0.3.3    tidyselect_1.2.0  munsell_0.5.0     lattice_0.20-45  
 [9] colorspace_2.1-0  R6_2.5.1          rlang_1.1.1       fansi_1.0.5       tools_4.1.2       grid_4.1.2        data.table_1.14.8 gtable_0.3.4     
[17] xfun_0.41         png_0.1-8         utf8_1.2.4        cli_3.6.1         withr_2.5.2       tibble_3.2.1      lifecycle_1.0.3   Matrix_1.6-1.1   
[25] vctrs_0.6.4       glue_1.6.2        compiler_4.1.2    pillar_1.9.0      generics_0.1.3    scales_1.2.1      jsonlite_1.8.7    pkgconfig_2.0.3  
   
5. For Seurat based sub-clustering of CosMx data; the following packages are used:
> sessionInfo()
R version 4.1.2 (2021-11-01)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Ubuntu 22.04.3 LTS

Matrix products: default
BLAS:   /usr/lib/x86_64-linux-gnu/blas/libblas.so.3.10.0
LAPACK: /usr/lib/x86_64-linux-gnu/lapack/liblapack.so.3.10.0

locale:
 [1] LC_CTYPE=en_GB.UTF-8       LC_NUMERIC=C               LC_TIME=en_GB.UTF-8        LC_COLLATE=en_GB.UTF-8     LC_MONETARY=en_GB.UTF-8   
 [6] LC_MESSAGES=en_GB.UTF-8    LC_PAPER=en_GB.UTF-8       LC_NAME=C                  LC_ADDRESS=C               LC_TELEPHONE=C            
[11] LC_MEASUREMENT=en_GB.UTF-8 LC_IDENTIFICATION=C       

attached base packages:
[1] grid      stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] reshape2_1.4.4         VennDiagram_1.7.3      futile.logger_1.4.3    stringr_1.5.0          corrplot_0.92          gplots_3.1.3          
 [7] spatstat_3.0-7         spatstat.linnet_3.1-3  spatstat.model_3.2-8   rpart_4.1.16           spatstat.explore_3.2-5 nlme_3.1-155          
[13] spatstat.random_3.2-1  spatstat.geom_3.2-7    spatstat.data_3.0-3    ggpubr_0.6.0           RColorBrewer_1.1-3     patchwork_1.1.3       
[19] ggplot2_3.4.4          sqldf_0.4-11           RSQLite_2.3.2          gsubfn_0.7             proto_1.0.0            dplyr_1.1.3           
[25] SeuratObject_5.0.0     Seurat_4.4.0          

loaded via a namespace (and not attached):
  [1] backports_1.4.1       spam_2.10-0           plyr_1.8.9            igraph_1.5.1          lazyeval_0.2.2        sp_2.1-1             
  [7] splines_4.1.2         listenv_0.9.0         scattermore_1.2       digest_0.6.33         htmltools_0.5.6.1     fansi_1.0.5          
 [13] magrittr_2.0.3        memoise_2.0.1         tensor_1.5            cluster_2.1.2         ROCR_1.0-11           globals_0.16.2       
 [19] matrixStats_1.0.0     spatstat.sparse_3.0-3 colorspace_2.1-0      blob_1.2.4            ggrepel_0.9.4         xfun_0.41            
 [25] tcltk_4.1.2           jsonlite_1.8.7        progressr_0.14.0      survival_3.2-13       zoo_1.8-12            glue_1.6.2           
 [31] polyclip_1.10-6       gtable_0.3.4          leiden_0.4.3          car_3.1-2             future.apply_1.11.0   abind_1.4-5          
 [37] scales_1.2.1          futile.options_1.0.1  DBI_1.1.3             rstatix_0.7.2         miniUI_0.1.1.1        Rcpp_1.0.11          
 [43] viridisLite_0.4.2     xtable_1.8-4          reticulate_1.34.0     bit_4.0.5             dotCall64_1.1-0       htmlwidgets_1.6.2    
 [49] httr_1.4.7            ellipsis_0.3.2        ica_1.0-3             pkgconfig_2.0.3       uwot_0.1.16           deldir_1.0-9         
 [55] utf8_1.2.4            tidyselect_1.2.0      rlang_1.1.1           later_1.3.1           munsell_0.5.0         tools_4.1.2          
 [61] cachem_1.0.8          cli_3.6.1             generics_0.1.3        broom_1.0.5           ggridges_0.5.4        fastmap_1.1.1        
 [67] goftest_1.2-3         knitr_1.45            bit64_4.0.5           fitdistrplus_1.1-11   caTools_1.18.2        purrr_1.0.2          
 [73] RANN_2.6.1            pbapply_1.7-2         future_1.33.0         mime_0.12             formatR_1.14          compiler_4.1.2       
 [79] rstudioapi_0.15.0     plotly_4.10.3         png_0.1-8             ggsignif_0.6.4        spatstat.utils_3.0-4  tibble_3.2.1         
 [85] stringi_1.7.12        lattice_0.20-45       Matrix_1.6-1.1        vctrs_0.6.4           pillar_1.9.0          lifecycle_1.0.3      
 [91] lmtest_0.9-40         RcppAnnoy_0.0.21      data.table_1.14.8     cowplot_1.1.1         bitops_1.0-7          irlba_2.3.5.1        
 [97] httpuv_1.6.12         R6_2.5.1              promises_1.2.1        KernSmooth_2.23-20    gridExtra_2.3         parallelly_1.36.0    
[103] codetools_0.2-18      lambda.r_1.2.4        MASS_7.3-55           gtools_3.9.4          chron_2.3-61          withr_2.5.2          
[109] sctransform_0.4.1     mgcv_1.8-39           parallel_4.1.2        tidyr_1.3.0           carData_3.0-5         Rtsne_0.16           
[115] shiny_1.7.5.1       

#### Running time: All R files run sequentially will take approximately 2 hours to run on a windows computer with 64GB RAM on a 4 core 3.4GHz machine 

#### Data files to run the analysis are available on Zenodo - 10.5281/zenodo.10402126

# Instructions for generating figures and analysis for leish-ME

## Description of technology used, associated code file and object it is dependent on

### Sri Lankan (SL) Cutaneous Leishmaniasis (CL) - Visium

    1. sl2_cl_integration.Rmd 
    2. sl2_cl_downstream.Rmd
         * Uses: with47_48_integrated_nd2117slcl_dims15_res0.9_prepsct.rds
    3. sl2_cl_cell2location.Rmd
         * Uses: with47_48_integrated_nd2117slcl_dims15_res0.9_prepsct.rds

### Sri Lankan (SL) Cutaneous Leishmaniasis (CL) - CosMx

    4. giotto_sl2_config.Rmd 
         * Uses: complete_giotto_object_PostAnalysis.RData
    5. giotto_sl2_downstream.Rmd
         * Dependent on giotto_sl2_config.Rmd
    6. cosmx_mac_sub_clustering.Rmd
         * Uses: SL2_seurat_object.Rds
    7. cosmx_mac_sub_clustered_downstream.Rmd
         * Uses: cosmx_myeloid_clusterf.Rds
    8. cosmx_spatial_plots.Rmd 
         * cosmx_clusterf.Rds

 ### Indian (IN) Post Kala Azar Dermal Leishmaniasis (PKDL) - Visium

    9. in_pkdl_integration.Rmd 
         * Uses .h5 files to generate lesion_PKDL_merged.Rds
    10. in_pkdl_downstream.Rmd
         * Uses lesion_PKDL_merged.Rds

 ### Brazilian (BZ) Cutaneous Leishmaniasis (CL) - Visium

    11. br_cl_integration.Rmd 
         * Uses .h5 files to generate lesion_BRCL_skin_merged.Rds
    12. br_cl_downstream.Rmd
         * Uses lesion_BRCL_skin_merged.Rds



| Figure number | File name           
| ------------- |:-------------:|
|1A|Images|
|1B|Images|
|1C|sl2_cl_downstream.Rmd|
|1D|sl2_cl_downstream.Rmd|
|1E|sl2_cl_downstream.Rmd|
|1F|sl2_cl_downstream.Rmd|
|1G|sl2_cl_downstream.Rmd|
|1H|sl2_cl_downstream.Rmd; plotted in GraphPad|
|1I|sl2_cl_cell2location.Rmd; plotted in GraphPad|
|Supp. 1A|Images|
|Supp. 1B|Images|
|Supp. 1C|sl2_cl_downstream.Rmd|
|Supp. 1D|sl2_cl_downstream.Rmd|
|Supp. 1E-K|sl2_cl_downstream.Rmd|
|Supp. 2A|sl2_cl_downstream.Rmd|
|Supp. 2B-L|sl2_cl_cell2location.Rmd|
|2A|Image|
|2A-D|giotto_sl2_config.Rmd|
|2E|cosmx_spatial_plots.Rmd|
|2F|cosmx_mac_sub_clustered_downstream.Rmd|
|2G|cosmx_mac_sub_clustered_downstream.Rmd|
|2H|cosmx_mac_sub_clustered_downstream.Rmd|
|2I|cosmx_mac_sub_clustered_downstream.Rmd|
|2J|cosmx_mac_sub_clustered_downstream.Rmd|
|Supp 3A|Images|
|Supp. 3B|giotto_sl2_config.Rmd. Plotted in GraphPad|
|Supp. 3C-H|giotto_sl2_config.Rmd|
|3A|sl2_cl_downstream.Rmd|
|3B|sl2_cl_downstream.Rmd|
|3C|sl2_cl_downstream.Rmd. Plotted in GraphPad|
|3D-K|sl2_cl_downstream.Rmd|
|3L|sl2_cl_cell2location.Rmd|
|3M-O|sl2_cl_downstream.Rmd|
|Supp. 4A|sl2_cl_downstream.Rmd|
|Supp. 2B|sl2_cl_cell2location.Rmd|
|4A|giotto_sl2_downstream.Rmd|
|4B|giotto_sl2_downstream.Rmd|
|4C|giotto_sl2_downstream.Rmd. Analysed in Excel, plotted in GraphPad|
|4D|giotto_sl2_downstream.Rmd|
|4E|giotto_sl2_downstream.Rmd|
|4F|Image|
|4G-I|giotto_sl2_downstream.Rmd  Analysed in Excel, plotted in GraphPad and UpsetR shiny app|
|5|Images, image analysis done in Strataquest and graphed in GraphPad|
|6A-F|giotto_sl2_downstream.Rmd; Graphed in GraphPad|
|6G-I|giotto_sl2_downstream.Rmd|
|6J|Analysed in excel and graphed in GraphPad|
|Supp. 5A|giotto_sl2_downstream.Rmd|
|7A-D|images|
|7E|br_cl_downstream.Rmd|
|7F|in_pkdl_downstream.Rmd|
|7G|br_cl_downstream.Rmd|
|7H|in_pkdl_downstream.Rmd|
|7I|br_cl_downstream.Rmd|
|7J|in_pkdl_downstream.Rmd|
|7K|in_pkdl_downstream.Rmd|
|7L|br_cl_downstream.Rmd|
|7M|Data from br_cl_downstream.Rmd,in_pkdl_downstream.Rmd and sl2_cl_downstream.Rmd. Plotted in Venny.|
|Supp. 6A-D|Images|
|Supp. 6E|in_pkdl_downstream.Rmd|
|Supp. 6F|br_cl_downstream.Rmd|
|8A-C|Flow data analysed in FlowJo and graphed in FlowJo and GraphPad|
|8D-O|Images; using data from source files plotted in R|

###Figure reproduction - Please use option 2 until publication
Option1 : Start from scratch using raw 10x files (available post publication)

    Download all samples/10x files from GSE290027. into source/'Visium_slide_name'/
    Start with sl2_cl_integration.Rmd, in_pkdl_integration.Rmd  or br_cl_integration.Rmd 

Option2 : Start from prepared Rds containing primary clustering analysis - 10.5281/zenodo.10402126

    1. Download all Rds files from the Zenodo repository - 10.5281/zenodo.10402126 and keep them in your working folder.
    2. Open Rmd file as per the figure needed from table above on RStudio. 
    3. Define working folder in the path (Find instructions in the Rmd file). 
    4. Create a sub-folder in your wokring path 'R'. All outputs will be saved here
    5. Run sequentially, chunk by chunk after all requisite packages are installed


 ### Cell2location: Deconvoluting spatial spots
Cell2location v0.1 (https://cell2location.readthedocs.io/en/latest/) was run by following the instructions as per the tool's tutorial for mapping lymph nodes. The code was run on University of York's HPC, namely, Viking using GPU node with 1 GPU, 1 node utilising 40GB RAM in approximately 2.5 hours. 1 hour for reference modelling and 1.5 hours for modelling the spatial data to calculate cell abundances in Visium spots

    Cell2location was installed in its own environment as per the instructions
    RAW single cell data (10.1126/science.aba6500) and RAW spatial data (this study) was used as input to cell2location
    Output was stored as a model.pt file and anndata file containing q05 abundances as metadata
    Python scripts were submitted to a job manager (slurm) on the HPC as a shell script with the following batch parameters and script

    #!/bin/bash #SBATCH --job-name=XXXX #SBATCH --mail-type=END #SBATCH --mail-user=nidhi.dey@york.ac.uk #SBATCH --ntasks=1 #SBATCH --cpus-per-task=1 #SBATCH --mem=40gb #SBATCH --time=04:00:00 #SBATCH --output=cell2loc.log #SBATCH --account=XXXX #SBATCH --partition=gpu #SBATCH --gres=gpu:1

    module load system/CUDA/10.0.130 
    module load lang/Miniconda3/4.9.2

    source activate cell2loc_env2

    command -v python

    python config.py

    source deactivate

    Abundances can be accessed from the final python object as metadata

    adata_vis.obs[adata_vis.uns['mod']['factor_names']] = adata_vis.obsm['q05_cell_abundance_w_sf']

    You can write this as a CSV file to explore abundances further as in sl2_cl_cell2location.Rmd

# License
## This project is covered under the MIT License.
