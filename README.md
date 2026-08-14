This project examines firearms recovered by the Louisville Metro Police Department (LMPD) primarily between 2010 and 2016, but entries up to February 2017 are also included. The intended dataset is the "Normalized" version, which is easier to find online than the raw original. As such, the Jupyter Notebook is written in a way that interacts with the columns of the normalized version. Portions may need to have columns renamed or code possibly rewritten entirely if one desires to examine the original. At the time of writing, this dataset is currently available at the below URL.
    https://data.louisvilleky.gov/datasets/02e1cf4e979444c3af5339e369c52d78_0/about

The project also incorporates a 2016 Crime Data dataset, (also from LMPD), to compare metrics of 2016 incidents known to involve firearm recovery to those which don't match an incident with a recorded firearm recovery. It is a stretch goal of this project to eventually expand its current scope to include Crime Data from all years in the Recovered Firearms dataset; especially years from 2010 to 2015. For now, the 2016 Crime Data dataset can be found at the below URL.
    https://louisville-metro-opendata-lojic.hub.arcgis.com/datasets/louisville-metro-ky-crime-data-2016/explore


It should go without saying that these files are necessary for the project to function. Additionally, the file names will need to be changed to:
    "Louisville_Metro_KY_Firearms_Intake_Normalized.csv"
    "Crime_Data_2016"
in order for the Jupyter Notebook to read them.

