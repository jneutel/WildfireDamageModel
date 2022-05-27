# Wildfire Damage Model
The model estimate health damage costs from CA wildifires.

Model requires use of jupyter lab and geopandas. It is recommended to make a new geo_environment (follow geopandas documentation). 

With the appropriate software installed, to use the model:
1) Open the User Interface in Jupyter Lab
2) Choose the year of interest. Optionally play with levers that control the fire day counting algorithm. Run the model. 
3) Specify display results. You can choose a list of counties or the whole state ["CA"]. You can also categorize results by age and by county, and choose to view on a per capita basis or a total basis. With those specified, run the cell to summarize your results. IMPORTANT: you DO NOT need to re-run the model (step 2) if you want to change your summary parameters. 
4) The results are data frames that you can do your analysis on. Some helpful plotting functions are already built for you, which plot the fire day counting algorithm and a map of your results. 
