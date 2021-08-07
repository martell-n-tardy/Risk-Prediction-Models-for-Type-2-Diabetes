# Risk-Prediction-Models-for-Type-2-Diabetes

## Getting BRFSS data
To get started, you'll want to download the data from the BRFSS Annual Survey Data page. There you can find links to each year the survey has been conducted. The data is available in .XPT (SAS Transport Format) or in .ASCII files. You should be warned that these are pretty big files, especially in more recent years. All together, the raw data is somewhere around 10GB.

It's easiest to use the files in Python if you convert them into .csv format. Downloading all the files and translating them into .csv is a pain, so I've done it for you. Since the .csv files are too large to host on GitHub, I'm making them all (2015-2019) available through my AWS account, and you can find them here. The codebooks however, for each year covered in this project, are available available in the "Codebooks" folder of this repository as a PDF, accept for 2019 which is [here](https://www.cdc.gov/brfss/annual_data/2019/pdf/codebook19_llcp-v2-508.HTML).
