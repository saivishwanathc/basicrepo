# Gun-Violence-in-the-United-States README
## Project summary
Gun violence is a public health crisis in the United States, claiming over 120 lives and injuring hundreds more. In the last ten years, there have been between 16,000 and 20,000 victims, according to estimates by Everytown and this repository. This crisis does not affect all states equally. Research shows there is a link between factors like population and the presence of regulatory legislature which might affect the incidence of mass shootings. 

This repository analyses gun violence data in the United States from 2015 to 2025, integrating metrics like population density, gun sales, number of victims, number of mass shootings, and gun regulation strength in order to elucidate on relationships and patterns. The data was extracted from the U.S. Census Bureau and various non-governmental organizations dedicated to the study and advocacy of gun violence prevention. 

The assumption in this study is that gun sales are related to the incidence of mass shootings, and that strong regulatory frameworks in turn, reduce them. However some of the results point at the fact these intuitive relationships are not nessarily reflected in the data. 

- The strength of gun regulation is related to population density, which might point at a relationship between historical evolution of mass shootings and the regulatory framework around gun sales and ownership.
- Higher indexes of law strength are not necessarily related to less shootings because there are states with similar mass shooting incidence as those with strong regulatory frameworks, however there are no states with high mass shooting incidence and high law strength while the states with a high law strenght present low mass shooting events.

For more information on the analysis, visit [this Tableau dashboard](https://public.tableau.com/app/profile/sai.vishwanath.chilukuri/viz/17042025_GunViolenceintheUS-CareerFoundryFinalProject_17468006503630/GunViolenceintheUS?publish=yes). 


## Key Project Questions 
- What state has the most mass shootings and gun sales?
- What state has the strongest regulatory framework and how many mass shootings has it had in the last 10 years? 
- How has the incidence of mass shootings behaved in the last 10 years?
- What is the relationship between gun sales and mass shootings?
- What is the relationship between population density and:
      - Mass shootings
      - Law strength
      - Gun sales
- What can geography tell us about mass shooting incidence and gun law strength? 

## Data sources
- Gun Violence Archive - [Mass shooting incidents between 2015 and 2025](https://www.gunviolencearchive.org/mass-shooting) (2025)
- The Trace - [Data Hub: Gun sales](https://datahub.thetrace.org/dataset/gun-sales/) (2025)
- Everytown Research - [Rankings of gun safety policy](https://everytownresearch.org/rankings/) (2025)
- U.S Census Bureau - [Population 2015-2020](https://www2.census.gov/programs-surveys/popest/datasets/2010-2015/counties/) (2020), [Population 2020-2024](https://www2.census.gov/programs-surveys/popest/datasets/2020-2024/counties/) (2025)
- Simplemaps - [U.S. County Coordinates](https://simplemaps.com/data/us-cities) (2025)

## File types
- Jupyter Notebook (IPYNB File)
- PDF
- Images (PNG File)
- Excel Worksheets

## Folders
The folders of this repository contain the following contents: 
- 01 Project Management: Documentation and project directives (Project brief)
- 02 Data: Original data (Excel files)
- 03 Scripts: Scripts for cleaning, wranging, visualizing, and analyzing (Jupyter notebooks).
- 04 Deliverables: Final report in Tableau format where the project's key questions are answered along visualizations, as well as detailed documentation of the project's development. 

### Prerequisites
The following libraries are necessary for the scripts to function
- pandas
- numpy
- seaborn
- os
- matplotlib
- folium
- geojson
- sklearn
- pylab
  
