The code folder contains seven .ipynb files. Please note the order in which they need to be run:

	1. build_static_features.ipynb
	2. build_crime_features.ipynb
	3. build_modelling_datasets.ipynb
	4. check_missing_lsoa.ipynb
	5. train_model_with_shap.ipynb
	6. dashboard.ipynb (See Appendix B for how to start this).
	7.data_analysis.ipynb

It should be noted that when others run this code, the data file may not exist. In this case, the relative location of the dataset needs to be modified manually.

The data folder contains the raw data sets required to run the code:
	census2021-ts006-lsoa-Population density
	census2021-ts007a-lsoa-Age by five-year age bands
	census2021-ts008-lsoa-sex
	census2021-ts021-lsoa-Ethnic group
	IMD2019
	MPS LSOA Level Crime (Historical)
	MPS LSOA Level Crime (most recent 24 months)
The remaining datasets can be used to run dashboard.ipynb directly. Please note that you still need to pay attention to the relative location of the datasets. Modify the file paths in the code as necessary.