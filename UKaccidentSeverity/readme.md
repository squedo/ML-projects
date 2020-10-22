# Capstone project

---

Car accident model - based on Data from the UK Department for Transport (2005-2014)

Data files provide detailed road safety data about the circumstances of personal injury road accidents in GB from 2005 to 2014:

- Accident file: main data set contains information about accident severity, weather, location, date, hour, day of week, road type…
- Vehicle file: contains information about vehicle type, vehicle model, engine size, driver sex, driver age, car age…
- Casualty file: contains information about casualty severity, age, sex social class, casualty type, pedestrian or car passenger…

---

# Introduction

Unfortunately, car accidents happen.

Therefore we will try to answer the following question: would it be possible to understand/predict the severity of an eventual accident for a car driver if ever happening? We will use easy to have variables to develop the model so that anyone can use it before driving it’s car. 

Such a predictive model could be interesting for instance for:
- Insurance companies to set a final price for products based on customer/drivers characteristics.
- For government authorities to forecast casualties that may occur during a 	year based on vehicles registered and drivers records and plan measures to reduce those casualties numbers.
- To generate awareness in individuals so that they are aware of the need of replacing their car, be even more careful when it rains or when it's a foggy day, etc.

We will be exploring the feasibility of creating such a predictive model based on variables that could be stored into the following categories:

- Driver data: age, etc.
- Time, road and environmental conditions: visibility, weather conditions, moment of the year, etc.
- Car specifications: engine capacity, driver side, etc.
- Parameters of the accident: speed, point of impact, etc.

Based on those variables the model would predict if the driver ever has an accident if it's going to be "fatal" or "Serious/Slight" with a certain confidence (binary classification problem).

To proceed we will be using the database published on Kaggle.com called "UK Accidents 10 years history with many variables" that collects accidents that took place from 2005-2014 in UK roads. Data are stored in 3 tables: accidents, vehicles and casualties and can be found in the following link:

https://www.kaggle.com/benoit72/uk-accidents-10-years-history-with-many-variables

Important to note that this database is likely to give insights and a prediction model to be used only for countries like the United Kingdom, Japan, Australia, India (more than 50 countries) where traffic happens from the left side.
