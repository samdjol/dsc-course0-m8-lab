# Aviation Accident Analysis

Aviation Accident Analysis is a Python module designed to analyze and assess the risk of injuries and plane destruction based on various flight accident data. It provides statistical insights into the factors that contribute to fatal or serious injury chances and the likelihood of aircraft destruction.

Flight accident data was filtered to include airplane accidents occuring after 1983 with the goal of finding recommendations for models based on risk. Both smaller and larger (size threshold = 20 passangers) plane recommendations were found. 

Aviation_Accidents_Cleaning.ipynb file cleans the provided AviationData.csv for analysis. Only professionally built airplanes were considered, and columns were constructed to assess risk of fatal/serious injury and destruction of the plane.  

In the analysis, plane recommendations for both large and small planes were found by creating a metric that aggregates plane makes and models by lowest risk. For small planes, the safest makes would be Waco, Maule, and Let. For large planes, Mcdonnell Douglas, Boeing, and Embraer could generally be considered the safest. 

Models followed a similar framework, filtering out models with less than 10 and 15 accidents on record for small and large planes, respectively. The Boeing 747 and Mcdonnel Douglas DC-9-51 were two large models with the lowest risk record. 

Limitations: With only accident records and no data on total flights recorded, the analysis focuses heavily on risk in the event of an accident. This analysis does not go into general probability of accident occurrences. 

Other metrics: Both weather condition and phase of flight variables were also examined. The conclusion from this analysis was that these variables had a major impact on incident risk, particularly poor visibility. The study suggests that plane make and model only are not clear indications of total risk. 
