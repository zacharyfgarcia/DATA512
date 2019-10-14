A2: Bias in Data
Name: Zachary Garcia
Date: 10/14/19

Goal:
The goal of this assignment is to explore the concept of bias through data on Wikipedia articles about political figures from a variety of countries.

Data sources:
To create these tables, I drew data from three sources. First was a list of Wikipedia articles about politicians with countries for each specified pulled from Figshare. Citation: Keyes, Os (2017): Politicians by Country from the English-language Wikipedia. figshare. Dataset. Source URL: https://figshare.com/articles/Untitled_Item/5513449.

Second was population data for all countries of the world as well as population rolled up into world regions, drawn from the world population datasheet published by the Population Reference Bureau. Source URL: https://www.prb.org/international/indicator/population/table. I downloaded the actual file WPDS_2018_data.csv from DATA 512's Canvas files page though. 

Third was the Objective Revision Evaluation Service (ORES) API which uses ML to estimate the quality of Wikipedia articles. 
Documentation URL: https://www.mediawiki.org/wiki/ORES

Resources used:
This analysis was prepared using Python 3.7.1 running in a Jupyter Notebook environment.
Documentation for Python can be found here: https://docs.python.org/3.7/
Documentation for Jupyter Notebook can be found here: http://jupyter-notebook.readthedocs.io/en/latest/

The following non-core/lib Python packages were used and their documentation can be found at the accompanying links:

pandas: https://pandas.pydata.org/pandas-docs/stable/
numpy: https://docs.scipy.org/doc/
oresapi: https://github.com/wikimedia/ores

Included Files:
hcds-a2-bias.ipynb - Jupyter notebook that includes commented code and walkthrough for reproducing all analysis done in this assignment. 

WPDS_2018_data.csv - Source data file for population data. See "Data sources" above.

page_data.csv - Source data file for politician wikipedia page data. See "Data sources" above.

wp_wpds_countries-no_match.csv - File that includes any incomplete rows in the world politician article quality dataset after data processing and merging took place such as politicians in countries with no population data found or countries that didn't match any politicians. See Jupyter notebook for more information. 

wp_wpds_politicians_by_country.csv - File that includes all complete rows in the in the world politician article quality dataset after data processing and merging. See Jupyter notebook for more information. 

README.txt - This readme.

LICENSE: This assignment code is released under an MIT license specified in the included LICENSE file. 
