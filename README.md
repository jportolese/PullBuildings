# PullBuildings
This jupyter notebook pulls buildings based on a drawn area of interest from the BING building footprint repository

When drawing the AOI keep in mind that a large area will take some time to download the buildings.  I recommend a small area that doesn't span too many tiles of the BING data in the later step

Output will be written in geojson format in the directory you ran the notebook in and it will be called Footprints.geojson

Read more about this data at 
https://blogs.bing.com/maps/2023-06/Bing-Maps-Global-Building-Footprints-released

This data is licensed by Microsoft under the Open Data Commons Open Database License (ODbL).
"Insert prominently in all relevant locations a statement such as (replacing {DATA(BASE)-NAME} with the name of your data/database):
Source the data with this:
This {DATA(BASE)-NAME} is made available under the Open Database License: http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/"
