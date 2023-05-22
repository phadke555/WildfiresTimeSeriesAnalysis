# WildfiresTimeSeriesAnalysis

Introduction: The 2020 wildfire season was one to remember. Amidst the devastating coronavirus pandemic and social justice issues, the 2020 wildfire season has burnt itself in our memory as one of the worst in history. In a span of 12 months, over 58 thousand fires raged throughout the country, burning through nearly 10.3 million acres. Threats of smoke inhalation led to mass evacuations and the loss of many homes, and it has forced families to move away in search of less fire-prone areas. These health and social impacts inspired us to study the past history of wildfire seasons in America to get a sense of what could happen in the future.

What was done: A time-series visualization and analysis of wildfires and associated deaths and injuries from 1996-2022 in the United States.

Method: It was important to take a look at past historical data to understand how the effects of climate change, wildfires, have raged through America. From the same source of data provided to us, we merged data from 1950 - 2021 with our current dataset from 2022. Wildfire data did not exist from 1950- 1996, so our visualizations began from 1996. We used python's builtin requests module and BeautifulSoup to extract the links to each dataset and download each of them. Then, using pandas, we decompressed each .csv file and then concatenated them together to create a singular, large dataset that we imported into Tableau for further analysis and visualizations. Timeseries visualizations were built in Tableau utilizing geographical location within the US to analyze the effects in terms of deaths, injuries, and value of property damaged.


Here is a link to the data: https://drive.google.com/file/d/1BYZJqNL3YfSc7ivZujR72Zqm9MDaY4ym/view?usp=sharing
