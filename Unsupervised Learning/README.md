## Unsupervised Learning Use case
---
### PART1

•`CONTEXT`: The  data  concerns  city-cycle  fuel  consumption  in  miles  per  gallon,  to  be  predicted  in  terms  of  3  multivalued  discrete  and  5 continuous attributes 

•`DATA DESCRIPTION`: The data concerns city-cycle fuel consumption in miles per gallon 

•`Attribute Information`: 
``` 
    1.mpg: continuous
    2.cylinders: multi-valued discrete
    3.displacement: continuous
    4.horsepower: continuous
    5.weight: continuous
    6.acceleration: continuous
    7.model year: multi-valued discrete
    8.origin: multi-valued discrete
    9.car name: string (unique for each instance) 
```
•`PROJECT OBJECTIVE`: Goal is to cluster the data and treat them as individual datasets to train Regression models to predict ‘mpg’ 

----
### PART2

•`CONTEXT`: Company X curates and packages wine across various vineyards spread throughout the country.

•`DATA DESCRIPTION`: The data concerns the chemical composition of the wine and its respective quality

•`Attribute Information`: 
``` 
    1.A, B, C, D: specific chemical composition measure of the wine
    2.Quality: quality of wine [ Low and High ]
```

•`PROJECT OBJECTIVE`: Goal is to build a synthetic data generation model using the existing data provided by the company.

---

### PART3
•`CONTEXT`: The purpose is to classify a given silhouette as one of three types of vehicle, using a set of features extracted from the silhouette. The vehicle may be viewed from one of many different angles.

•`DATA  DESCRIPTION`: The  data  contains  features  extracted  from  the  silhouette  of  vehicles  in  different  angles.  Four  "Corgie"  model  vehicles were used for the experiment: a double decker bus, Cheverolet van, Saab 9000 and an Opel Manta 400 cars. This particular combination of vehicles was chosen with the expectation that the bus, van and either one of the cars would be readily distinguishable, but it would be more difficult to distinguish between the cars.•All the features are numeric i.e. geometric features extracted from the silhouette.

•`PROJECT OBJECTIVE`: Apply dimensionality reduction technique – PCA and train a model using principal components instead of training the model using just the raw data
