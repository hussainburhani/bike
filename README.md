![](./images/bike1.jpg)

## Cycling through data science &nbsp; <img src="../master/images/bicycle32.png" style="float:right">

### General Cycle: a bicycle-for-hire startup
General Cycle is a startup that rents bicycles at select metro stations in DC. Since space to store the bikes at the stations is very limited and prohibitively expensive, the company maintains a small storage hub in DC. However, their main storage facility is located in Bowie, Maryland, and is central to their operations in DC, Baltimore, and Annapolis.

Each morning, a delivery truck transports bikes from the Bowie location to each of the storage hubs in DC, Baltimore, and Annapolis. A smaller delivery van is then able to more quickly stock each of the metro station locations as needed. However, it has proven to be very difficult to estimate how many bikes should be transported to each of the three storage hubs, as well as how often during the day.  

The startup is still in its early stages and has limited resources. Given that I recently returned from the country of bicycles, am a newly minted data scientist, and delved in the startup scene as well, have been asked by the operations manager, who also once took a data analytics course, to help solve the logistics issue of predicting daily demand. She is most interested in me first looking at their DC location since it is the most crucial of the three markets. She is also most concerned about transporting bikes to and from Bowie to DC as the stakes are much higher given the longer commute times, the costs of paying the trucking company, and lost sales.

### Inspiration
Having spent the last two years in a university town outside Amsterdam, it is impossible for me to escape on two feet. Bicycling is so tightly integrated into Dutch culture that there are more bikes than people, certification exams for school children, an entire dedicated public infrastructure, and is the primary means of transportation in the country. The world's largest bicycle garage in Utrecht is a marvel and an excellent example of classic Dutch style blended with tastefully implemented modern technology. I fit right in since I hadn't owned a car in at least a decade, rode around in Baltimore and DC on a single-speed with coaster brakes, and preferred indulging in spa culture than splurging on a gym spin class. But that's a topic for another conversation--for now "Geniet van het fietsen!".

### My pitch
My pitch to the team is titled "Cycling through data science," and illustrates the basic modeling framework for setting up the data science problem, gathering and exploring the appropriate data, building and evaluating the model, and answering the problem at hand. Specifically, I am searching for a dataset that may serve as a proxy for ascertaining the number of bikers in any given day, and understanding how particular features may help explain the variability of the number of users.


## Tackling the problem

### Framework
- Define the data science problem
- Gather the data
- Explore and transform the data
- Build the model
- Evaluate the model
- Answer the problem

### Data science problem
> Gather and utilize features which might help predict the number of bike users in any given day in DC.

*Regression* problems are inference problems in that we infer, or predict, parameters of a population from a sample. They are also specifically supervised learning problems that entail building a model to make predictions about a continuous target variable (where the variable is comprised of uncountable values).


## Datasets 
- [Capital Bikeshare (aggregate hourly and daily)](./code/eda_capital_bikeshare_historic.ipynb)
- [Capital Bikeshare](./code/eda_capital_bikeshare.ipynb)

## Deliverables
A Jupyter notebook, [mlr_general_cycles.ipynb](./code/mlr_general_cycles.ipynb), for which a structured format is provided to follow through with the code, modeling, and analysis and which also describes some of the data with visualizations and statistical analysis. In addition some exploratory data analysis is provided in the notebook files under Datasets.
A README markdown file, [this file](./README.md), which provides an introduction to and an overview of the project.
A presentation [slideshow](./slides/capstone_bike.pdf) rendered as a .pdf file. The included presentation, intended for a semi-technical audience, was presented to the class on February 12th, 2019.

## Technical Report and Implementation
I used the [mlr_general_cycles.ipynb](./code/mlr_general_cycles.ipynb) Jupyter notebook to outline the entire process, and is meant to showcase the methodology and implementation for defining the problem, gathering, exploring, and tranforming the dataset, and building, fitting, and evaluating the model to answer the data science question. I have provided commenting and context as much as possible, but in essensce, it is a rather raw working file to provide both methodology and future reference.

In addition, this truncated copy of the technical report [the live product demo](./code/mlr_general_cycles_demo.ipynb) includes a tool which can be used to predict the number of bikers in any given day in DC.

## Executive Summary

- Situation  
  Logistics at General Cycle and issues with current methodology.
  
- Business problem  
  Gather and utilize features which might help predict the number of bike users in any given day in DC

- Feature selection and modeling  
  Linear regression process  
  Data categories  
  Correlations of features  
  Normality of target  

- Prediction tool  
  Live demonstration of prediction tool for General Cycle  
  
- Future improvements  
  Insights on how and what to build upon existing work  

- Coda  
  Broad overview of problem, analysis, and resolution  
