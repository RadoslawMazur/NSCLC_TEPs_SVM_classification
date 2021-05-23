# NSCLC_TEPs_SVM_classification

Description: <br>
This is a small pliot study performed within the scope of my Bachelor's thesis as perliminary data. SVM algorithm was implemented along with other compuational methods (e.g., PCA) to classify samples into NSCLC or non-cancer groups based on tumor educated pletelets expression profiles. Sci-kit learn implementation of algorithm was used. For data wrangling we used numpy and pandas. Matplotlib was used for visualization.
<br>

Data:<br>
-Non-cancer donors (asymptomatic controls, 43% males and 57% females; median age of 58; n = 377).<br>
-NSCLC patients (late-stage metastasized or locally advanced; 53% males and 47% females; median age of 61; n = 402). <br>
Source: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE89843<br>
<br>
Files description:<br>
*normalization.Rmd* - R script used for normalization ofthe sampels. TMM was used, as implemented by edgeR package.<br>
*TEPs_SVC_NSCLC_algorithm_dev.ipynb* - Python notebook containing all other elements of the study, with algorithm training.<br>
<br>
Results:<br>
![charts](https://user-images.githubusercontent.com/76619482/119267789-58207780-bbf0-11eb-8dfb-c64398d1d347.png)
