R code to accompany the paper ``Bayesian   Pairwise Comparison of  High-Dimensional Images’’ by Subharup Guha and Peihua Qiu (2024). The R code partially implements the simulation strategy described in the paper by generating similar and different image pairs and fits them using the novel spatial random partition model (sRPM) proposed in the paper. It then analyzes each image pair using the sRPM technique and calls each image pair similar or different. 

How to run the code
1.	For tt=1,…,500, run “main.R” in parallel in batch mode. The value of tt comes from the environment variable passed by Linux
2.	Move the 500 files RData files to a newly created “RData” folder. 
3.	Download RData folder into the local folder.
4.	Run “collated_main.R” locally. The generated PDF file is the ROC plot. 

