![image](https://user-images.githubusercontent.com/90293333/162963880-a90892d4-c2a5-4df7-91bc-1e23c85e9f45.png)

<div align="center">

    
# README

### by Joann Balraj 
### April 8, 2022

</div align="center">
    
<hr style="border:3px solid black"> </hr>

#### Dataset obtained from Kaggle: https://www.kaggle.com/datasets/shrutimehta/nasa-asteroids-classification


# Project Description
#### "The data is about Asteroids" - NeoWs.
> "NeoWs (Near Earth Object Web Service) is a RESTful web service for near earth Asteroid information. With NeoWs a user can: search for Asteroids based on > their closest approach date to Earth, lookup a specific Asteroid with its NASA JPL small body id, as well as browse the overall data-set."  - https://www.kaggle.com/datasets/shrutimehta/nasa-asteroids-classification

### Overview & Plan:
> I will be taking a look at the factors that might be useful to identify an asteroid as potentially hazardous or not. I will also be analyzing the classification power of those remaining factors in the absence of absolute magnitude and minimum orbit intersection values.
<hr style="border:2px solid black"> </hr>

# Project Goals:
- Use the Asteroids Classification data offered by NASA through Kaggle.com. 
- Analyze the factors that categorize asteroids & use that to predict when asteroids will be hazardous or not. 

<hr style="border:2px solid black"> </hr>

# Project Planning
## Plan -> Acquire -> Prepare -> Explore -> Model & Evaluate -> Deliver

<b>Planning:</b>  
- Create a README file ✅

<b>Acquisition </b>  
- Gather NASA: Asteroids Classification (.csv) from https://www.kaggle.com/datasets/shrutimehta/nasa-asteroids-classification

<b>Preparation</b>  
- Create a `workbook.ipynb` file to put all work in 
- Clean aquired asteroid data:
    - remove missing values 
    - inspect data integrity issues

<b>Exploration and Pre-processing</b>  
- Explore Hazardous Nature - Is the asteroid hazardous? (True or False)
  -  Orbit Uncertainity vs. Hazardous Nature
  -  Absolute Magnitude vs. Hazardous Nature
  -  Minimum Orbit Intersection vs. Hazardous Nature
  -  Perihelion Distance vs. Hazardous Nature
  -  Est Dia in KM(min) vs. Hazardous Nature
  -  Eccentricity vs. Hazardous Nature
  -  Relative Velocity vs. Hazardous Nature

<b>Modeling</b>  
- Separate the variable of interest as the response variable and all the other variables as the predictor variables.
- Split data set into train and test

- Establish and evaluate baseline model
- Create at least 4 different models and compare their performance
- Use confusion matrix and ROC curve as the model evaluation metrics



<hr style="border:2px solid black"> </hr>

# Steps to Reproduce

You will need to obtain the `GlobalLandTemperaturesByMajorCity.csv` file from https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data to use for the project.

 1. Read this README.md 
 2. Install necessary packages
 3. Run the `Final_Report.ipynb` in a jupyter notebook.
