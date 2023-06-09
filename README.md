##Overview
This repo contains necessary datasets and codes to generate results of our project, which focuses on re-analyzing saliva metabolome profile generated by Narjes et al. 
The data folder contains the original and later pre-processed data for uploading to Google colab for further analysis. The dataset are named by dates. 
The code folder contains current code necessary to generate results and figures in the Result folder. There is no non-standard method. Currently it only contains code for 
generating a bar graph to visualize group size in this study.

##Data
The data we used here is saliva metabolome profile from 170 Covid-19 patients with different disease severity. It contains individual metabolite intensity obtained by the
authors. We believe the saliva metabolome data can be a great source to identify Covid-19 biomarkers and enriched pathways. The results can also be used to compare with
other metabolic study using other types of sample.
Citation: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9589589/ 
Saheb Sharif-Askari, Narjes et al. “Saliva metabolomic profile of COVID-19 patients associates with disease severity.” Metabolomics : Official journal of the Metabolomic Society vol. 18,11 81. 22 Oct. 2022, doi:10.1007/s11306-022-01936-1

##Folder Structure
The Data folder contains the original and later pre-processed data for uploading to Google colab for further analysis. The dataset are named by dates. 
The Code folder contains current code necessary to generate results and figures in the Result folder. There is no non-standard method. Currently it only contains code for 
generating a bar graph to visualize group size in this study.
The Result folder contains the analysis result and figures generated by this project. Currently only contains a bar graph showing group size.

##Installation
The code is in .ipynb format, and could be uploaded and run on Google Colab. All the necessary import is in the code and the version is by default. 
Upload the 20440_pset4_figure_code.ipynb to Google colab, and upload dataset_processed.xlsx when prompted. Then run through the all code blocks to the end.
