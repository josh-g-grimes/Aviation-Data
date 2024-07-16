# Harry Jannerone Needs Analysis
![download](https://github.com/user-attachments/assets/8cc07eef-2914-43a9-9930-31aa5a5adac8)

__Author:__ [Joshua G Grimes](https://www.linkedin.com/in/joshua-g-grimes/)

## Overview
This project analyzes the aviation accident data from the [National Transportation Safety Board](https://www.ntsb.gov/Pages/home.aspx) (NTSB) in order to determine which airplane model is the least risk for Harry Jannerone to sell. A descriptive analysis of injury rates determines that specific models of airplanes have fewer fatal, serious, and minor injuries when that model is involved in an accident versus other models.

# Business Problem
![airplane accident](https://github.com/user-attachments/assets/45a218b5-258a-4e60-9d9e-48a7430912ae)

Harry Jannerone has just been laid off from Dunder Mifflin Paper Company and wants to accomplish his dream of selling one big thing, like an airplane, and then retiring. Whether caused by pilot error or mechanical problems, any person suffering from an injury or property loss because of a flying accident can take you to court. Therefore, Mr. Jannerone wants to know which airplane has the lowest risk for his endeavor. Using the accident data from the NTSB, I describe patterns in the number and types of injuries that occur in airplane accidents to determine which airplane model will have the lowest risk and give Mr. Jannerone a resource to use in his sales attempt.

# Data 

The NTSB aviation accident database contains information from 1962 and later about civil aviation [accidents](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) and selected incidents within the United States, its territories and possessions, and in international waters. Every accident has a unique ID associated with it. The data files proved the date, location, airport, weather condition, injury information (fatal, serious, minor, uninjured), and aircraft information (make, model, number of engines, engine type, registration number, etc.).

# Methods
This project uses descriptive analysis to provide useful insights into aviation accidnts. 

# Results
Fewer people are injured in accidents that occur in specific types of airplanes which provides less risk to the owners of those airplanes from a litigation standpoint.  Professionally-built, turbo fan or jet airplanes with three or four engines. 

![Uninjured_characteristics](https://github.com/user-attachments/assets/105bce43-0781-4303-93b1-c4b353d426e3)


There are also specific makes and models of airplanes that have a fewer percentage of passengers that are injured when they are involved in accidents on their aircrafts. 

![Uninjured by Make-Model](https://github.com/user-attachments/assets/cada77e6-2315-4bcf-94aa-13f8c6c855a9)

# Conclusions
This analysis leads to three recommendations for choosing an airplane for Mr. Jannerone to sell. 

-  __Do not attempt to sell a small single or double engine aircraft__  Over 40% of the people who have been involved in an accident in a one or two engine plane have been injured. A three or four engine airplane will have the lowest risk for passengers being injured if they are in an accident. 
***
- __Sell a turbo fan or a turbo jet engine airplane__  Over 90% of the passengers who are involved in an accident while flying in a three or four engine airplane that has a turbo fan or a turbo jet engine are uninjured in the accident. This will provide the least amount of risk for Mr. Jannerone. 
***
- __Sell an Airbus A-340 or A380__ Mr. Jannerone will have a huge selling point to make to future investors if he works with Airbus.  Only 4% of the passengers on Airbus A-340 models have been injured in accedents and nobody has been injured in any accidents that occured in an Airbus 380.  

## Next Steps
Further analyses could yield additional insights into the decision for which type of Airplane Mr. Jannerone should sell: 

- __Better understanding of low risk airplanes from data on planes that aren't in accidents__  Modeling the percentage of airplane models that take flights and aren't involved in accidents may give a better understanding of which planes are the lowest risk. 
***
- __Predicting accident scenarios by airplane model__ This modeling could make it possible to lower the risk of all airplane models by helping fewer people be injured in accidents. 
***
- __Model Pilot Data__ This modeling could use already available data to see how much of the airplane risk is the model of the airplane and how much has to do with pilot training, flight hours, crew rest, etc.

# For More Information

See the full analysis in the [Jupyter Notebook](https://github.com/josh-g-grimes/Aviation-Data/blob/main/notebook.ipynb), review this [presentation](https://docs.google.com/presentation/d/1dTMOULknZKu12ylVUpjkd1nI3PPCsLezI0jKpaleO_E/edit?usp=sharing), or visualize the data on this [Tableau dashboard](https://public.tableau.com/views/AviationAccidentDataAnalysis-JoshuaGrimes/AviationAccidentData?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link). 

For additional info, contact Josh Grimes at josh.g.grimes@gmail.comm

# Repository Structure

|--- .gitignore

|--- README.md

|--- notebook.ipynb
