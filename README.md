# Demographic-Transition-Model---Jupyter-Notebooks

For my project I decided to create a Demographic Transition Model (DTM) from human geography. The focus of a DTM is to show development level in a country based on the following population indicators:

1. Crude Birth Rate 
2. Crude Death Rate
3. Total Population

The original model theorized that countries pass through 4 stages of development, however more recent versions of the model use 5 stages-  something I decided to test in my project. 

It was particularly interesting to me because just from looking at the DTM one can find areas of “natural increase” (increasing population), “natural decrease”(decreasing population), population projections based on the death and birth rates, effects of pro-natalist or anti-natalist policy changes in a country and the population momentum (as seen for China), impacts of war (Baby Boom of the 1960s in Canada), dependency ratios (Germany) etc.


Gathering data for something like might be painful - but well I literally just went to this website- 
https://ourworldindata.org/world-population-growth/#demographic-transition

Jumped to the DTM made on their site, went to their citations, and used the same csv files they used; which fortunately had the data for every country! 


So I cleaned up the csv to only have information about the country name, birth rates, death rates, total population and years. It was then defined using Compund Data and Lists like so:
