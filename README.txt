This archive contains all the relevant code for the paper 'Uncertainty Quantification in Binary Classification via Latent Quantile Estimation'

The main notebook, called BQR.ipynb has a walkthrough of all the topics presented in the main paper for a single dataset.
Code for individual components can be found in the Individual_Experiments folder. Some of the topics, such as robustness and interpretibility have not been described in the main work but merely mentioned in the conclusion.

The dataset folder contains most of the datasets used. Some have been omitted to save space, namely Redshift and the image archives.

Links to the image archives can be found in the ImageResults folder.

The redshift data can be obtained from here : https://www.sdss.org/dr16/data_access/
You will have to create a Casjob to pull the required data. The range of redshift values is 0 to 7.
The features selected were: modelMag u’, ’modelMag g’, ’modelMag r’, ’modelMag i’, ’modelMag z’, ’modelMag ug’, ’modelMag gr’, 
’modelMag ri’, ’modelMag iz’, ’fiberMag u’, ’fiberMag g’, ’fiberMag r’, ’fiberMag i’, ’fiberMag z’, ’fiberMag ug’, ’fiberMag gr’, ’fiberMag ri’, ’fiberMag iz’, ’petroR50 rr’,
’petroR90 zz’, ’ri’, ’iz’, ’dered u’, ’dered g’, ’dered r’, ’dered i’, ’dered z’, ’petroMag uu’, ’petroMag gg’, ’petroMag rr’, ’petroMag ii’, ’petroMag zz’
For IMDB, please download the 50K review version, create a new folder under datasets named IMDB, and place the Train and Test csvs in that folder

Refer to the dataset_params file for details on how to use the datasets in the notebooks 
