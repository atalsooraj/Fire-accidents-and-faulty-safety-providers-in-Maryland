The datasets I chose pertain to fire safety deficiencies and related incidents in USA. The data sources for these datasets 
are https://catalog.data.gov/dataset/fire-safety-deficiencies-61a6 and https://apps.usfa.fema.gov/civilian-fatalities/incident/reportMap.
I discovered these datasets while searching for fire accident incidents across USA when I came across this interesting dataset.
These datasets are an open source and freely available to access and download. They are legal and do not violate any rules. 
I browsed to check if someone had previously carried out an EDA on these data sets but did not find any citations or research papers related to it. 
The datasets contain: 157428 rows , 20 columns and 1838 rows, 12 columns respectively. The file sizes are 48.3 MB and 500 Kb. The datasets
have data types like object, int and bool. The primary co-relation between the two datasets is the name of states in each dataset that I
will use to merge them. The first dataset contains types fire safety deficiencies, safety providers, addresses etc. The second dataset 
provides description of fire incidents, loss due to this fire, location etc. The datasets have missing values for a few columns that need 
to be accounted for later in the data cleaning process.

After my preliminary inspection of the datasets I have framed a hypotheses that could be judged after my final analysis:

A state having the highest fire safety deficiency has the highest number of fire incidents
A question I would like to answer after my final analysis is:

Were there any fire safety providers near the locations(within 5 km) of fire accident?
