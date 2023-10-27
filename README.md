Mel Beall � DA09:
NSW 

Motivation

       After working for years on sheep and goat farms, I became fascinated by the impact of animal grazing on soil health. Through field observation, it was clear that intensive rotational grazing could have a massive impact in soil improvement over time, but free roam grazing would have the opposite effect.

Motivation
My passion for knitting led me to learn about wool production, growing natural dye plants, and eventually vegetable and ruminant farming. It was in the fields where I learned about rotational grazing and witnessed its profound impact on ecological restoration. My interest in textiles combined with my concern for the climate crisis we are currently living through causes me to turn my attention to grazing and wonder how we can allow the animals we foster to rebuild a healthy living planet. 


Background

The final piece of the carbon cycle is grazing. Most of the biomass in grass, or any other plant, is tied up in complex polymers like cellulose and lignin, which are a stockpile of stored solar energy. This solar power is completely inaccessible to humans, but it is indirectly accessible to cattle. Cattle are part of a group of animals called ruminants, along with sheep and�bison that chew the cud regurgitated from their rumen. Rumen is the first stomach of a ruminant, where food or cud is received and partly digested with the aid of bacteria, before passing on to another part of the animal�s digestive tract.

Dr. Allen Williams, Ph.D.

The Data
	
	The New South Wales Grazing Assessment is a large collection of datasets spanning fifty-four grazing sites collected over three years. 

Three soil types � silt, sand, clay
Three animals � livestock (goats, sheep, deer, cattle), kangaroo, rabbits
Three measures of soil chemistry � ph, phosphorus, carbon
Three communities � Redgum, Cypress Pine, Blackbox

The goal of my project is to discover any correlation between animal grazing and overall soil quality. While I have personally seen intensive rotational grazing positively impact soil health and biodiversity, I will be curious to see if the mixture of landscapes represented as well as mix of wild and stock grazing may in fact show over-foraging and soil depletion.

	My questions: how do we measure soil quality? Which animals are the major grazers? Which plants are the major growers?


Data Question
What is the ideal range of grazing diversity (wildlife and animal stock) in the Australian regions studied? Does more intense grazing always correlate to poorer soil health? What are acceptable parameters that indicate soil health? Is there any data to support some grazing is beneficial to soil health?

There are some technical terms I will need to read up on to understand what the data is documenting related to chemicals and animal markings. For example: what is soil stability or infiltration and what can it tell us about soil health? The Data Quality Statement provided indicates it will be necessary to contact the Custodian for the dataset for this information. I am also curious how livestock grazing is practiced in these areas.
�INTERPRETABILITY Fair .� Find out more about ambiguous or technical terms used in the data from the Custodian (contact details below).�  -pdf (nsw.gov.au)

The Cornell Soil Health Testing Lab uses these indicators to provide a comprehensive assessment of soil health:

CHEMICAL MAKEUP
pH phosphorus, potassium, magnesium, and zinc

BIOLOGICAL CHARACTERISTICS
Organic Matter: Carbon-rich material derived from living organisms
Soil Protein: Nitrogen bound in the soil
Soil Respiration: Rate at which the microbial community breaks down organic matter
Active Carbon: Organic matter that can serve as a food source for soil microbes

PHYSICAL PROPERTIES
Soil Texture: Makeup of sand, silt, and clay
Water Capacity: How much plant-available water the soil can hold
Aggregate Stability: How well soil particles can hold up to disturbances
Soil Compaction

FOUR SOIL HEALTH PRINCIPLES
Minimize Disturbance
Maximize Continuous Living Roots
Maximize Biodiversity
Maximize Cover

Technologies
For most of the project, I used a Geospatial Conda Environment and Python 3 within a Jupyter Notebook, mainly working within a Folium to visualize the data interactions required for analysis. The four datasets used were retrieved from the website operated by the government of the Australian state New South Wales. The datasets were downloaded as CSV files in Excel where I then used pivot tables to visualize the data. I also used Tableau to visualize during my Exploratory Data Analysis, but ultimately relied on Excel and Python for the bulk of my analysis

Problems & Hurdles


Normalizing the Data
One thing that might become evident in examining the created dashboard tool is that the analysis of the AADT by county is a summation of a particular traffic station's AADT. This means that certain counties, like Davidson and Rutherford, may perhaps have a higher sum AADT than other counties because they have more traffic stations collecting data. I realized a bit to late that this might skew the analysis and therefore the data is left unnormalized. However, I believe that this doesn't greatly alter what is the reality of the high volumes of traffic that those counties do see.
Hurdles
Although I collected data on the change in AADT over time and was able to plot this on a line graph, I was unable to get Power BI's ArcGIS map feature to smoothly run to show a time lapse of the growing volume of traffic over time.
Link to Dashboard
https://app.powerbi.com/groups/me/reports/7b2f603e-5cad-4b84-ac2d-c8382e6a311e/ReportSectiona0519b7ce424d578cf59

