# Infection Model
This project was made as a part of Math 418 (Mathematical Modeling) with Dr. Palmer at Dakota State University. The goal of the project was to model the spread of an infectious disease across a population. The model takes into consideration friend circles, random contacts, and different stages of infection. I also accommodate a few methods of modeling preventative measures. RandomTesting accounts for a constant amount of random testing weekly. Usage of masks can be accounted for by decreasing infection rates per interaction. Social distancing can be accounted for by decreasing the mean number of daily contacts per person.


## Built with:
Jupyter Notebook
Python
pandas, numpy, matplotlib

## Model information:
-Each individual has a mean daily average of contacts, taken from a Poisson distribution.
-Each individual has a maximum number of friends, taken from a Poisson distribution.
-Every day, individuals are given a random allotment of contacts based on their daily average. 
-Individuals gain friends as the model runs and have a higher chance of coming into contact with them.
-Individuals who are unaware of their status have a random chance to be tested once a week. Individuals who test positive avoid social contact.

## Contact
Email: eddie.french@trojans.dsu.edu