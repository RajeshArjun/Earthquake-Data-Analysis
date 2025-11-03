# Earthquake Data Analysis 

Goal: The goal of this project is to analyze global earthquake data to identify factors that contribute to the significance of an earthquake event.
Specifically, this analysis examines whether variables such as distance, depth, and magnitude can predict how significant an earthquake is, as measured by the significance variable provided in the dataset.

Data Context: The dataset was obtained from the United States Geological Survey (USGS), which continuously monitors and reports the causes, effects, and hazards of earthquakes worldwide.It contains information such as:
Distance – the approximate distance from the reporting station (in km)
Depth – the depth of the event (in km)
Magnitude – a measure of the earthquake’s size at its source
Significance – a numerical value indicating the relative importance or impact of the earthquake
Each record also includes the geographical coordinates and a brief location description for earthquakes occurring around the world.

Content Summary/Findings: In this analysis, we investigated factors influencing the impact significance of earthquakes worldwide. The outcome variable is significance, while the predictor variables are distance from the reporting station, depth of the earthquake, and magnitude. Key findings include:

Distance from reporting station: Moderate positive correlation with significance 
𝑟=0.54 , suggesting that farther earthquakes tend to be reported with higher significance.

Depth of earthquake: Moderate positive correlation 
r=0.40, indicating that deeper earthquakes are generally associated with higher impact significance.

Magnitude: Strong positive correlation 
r=0.91, showing that larger earthquakes have a significantly higher impact significance.

Files Attached:

Final Draft 1.rmd -> All analysis for this project was performed in an R Markdown (.Rmd) file, which contains the R code, visualizations, and statistical summaries. The .Rmd file allows for a reproducible workflow, combining code, output, and narrative explanations in a single document.

Citation -> Library.usgs.gov
