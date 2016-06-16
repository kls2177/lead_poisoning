# lead_poisoning

Lead poisoning in children from paint, pipes and contaminated soil remains a serious public health concern, despite decades-old bans on leaded paints and fuels. Recent events in Flint, Michigan have highlighted the devastating health effects that lead poisoning can have and how these effects are often stratified along socio-economic lines.

Here, I explore the childhood lead poisoning statistics for New York City and New York State and develop a prediction model for lead poisoning risk, using coarsely-grained American Community Survey (2014) data. These prediction models shed some light on the neighbourhood and county demographics and economics that expose children to higher risk of lead poisoning.

A summary of the analysis and data sources can be found in the following blog:

http://kls2177.github.io/lead/

## The analysis was completed in two IPython Notebooks:

*Note: Be sure to change the "rootpath" in the notebooks, if necessary.*

NYC Lead Poinsoning.ipynb (this analysis was done first, so please look at this one first.)

NY State County Lead Poisoning.ipynb

## The python package requirements are listed in the following file:

requirements.txt

## The full list of the data sources I used is here:

#### NY State BLL data:

https://health.data.ny.gov/Health/Childhood-Blood-Lead-Testing-and-Incidence-of-Bloo/d54z-enu8

#### American Community Survey 2014 tool for data extraction:

http://mcdc.missouri.edu/cgi-bin/broker?_PROGRAM=websas.acsmcdcprofiles_extract_menu.sas&_SERVICE=appdev&st=36

#### American Community Survey geographical shapefiles for NYC zipcodes and NY State counties:

*Note: The zipcode shapefile is included in the data directory but the county shapefile was too large to upload to github. This will need to be downloaded by the user to their local repo.*

ftp://ftp2.census.gov/geo/tiger/TIGER2014/

#### New York City Lead Poisoning Reports:

http://www.nyc.gov/html/doh/downloads/pdf/lead/lead-2012report.pdf

http://www.nyc.gov/html/doh/downloads/pdf/lead/lead-2009report.pdf
