# Data-Viz-Poster-Presentation

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [References](#references)

### Project Overview
This project provides an exploratory analysis of Washington State census data on Native Reservations. In particular, it highlights several custom data visualizations to both demonstrate the limits of US census data about Native peoples and to counter negative stereotypes implicit in the data.

### Data Sources
Data is from the US census portal “My Tribal Area” (available at https://www.census.gov/tribal/?st=53) which is based on 2015-2019 American Community Survey 5-year Estimates. Data were downloaded separately for each “Tribal area” listed in Washington state and then compiled to create one merged dataset. 

Of note, this dataset reflects census data gathered on census-designated reservations, off-reservation trust land, and Tribal Designated Statistical Areas (TDSA). It does not reflect data gathered solely on enrolled or self-identified Native people.

### Tools
Raw data was compiled and organized in Excel, while the data analysis and modeling was completed in R. Specific libraries used in R for this project include:

- Readxl
- Dplyr
- Tidyr
- Data.table
- Tibble
- Ggplot2
- RColorBrewer
- Stringr
- Tmap
- Sf
- Scales
- Ggrepel

### Data Analysis
 
I created four charts to explore the difference in location, population, racial distribution, and income for “Tribal Lands” in Washington state, with a focus on the difference between coastal areas along the Salish Sea and interior areas east of the Cascades.

![WA](https://github.com/lucaskolson/Data-Viz-Poster-Presentation/assets/91341415/ebba107c-95a6-45bc-9fa9-b700b5343930)

![q](https://github.com/lucaskolson/Data-Viz-Poster-Presentation/assets/91341415/f99d427b-1391-4d67-a88a-23efed880a04)

![p](https://github.com/lucaskolson/Data-Viz-Poster-Presentation/assets/91341415/80f81f41-2e4a-4f33-9944-b856d860e2a5)

![r](https://github.com/lucaskolson/Data-Viz-Poster-Presentation/assets/91341415/daadaade-8334-4ce6-b3c8-fb1f0b4f1ee1)



### Results
No significant differences were found between coastal and interior Tribal lands in regards to population, race, or income. However, the data suggests a much more diverse racial and income distribution on Tribal Lands than negative stereotypes of poverty-stricken reservations. Accurate measurements are not available about enrolled and self-identifying Native people to allow for more nuanced analysis.

### References
Jacobs B. Connolly, M. Counting indigenous American Indians and Alaska natives in the us census. Statistical Journal of the IAOS, 36(1):201-210, 2020.
