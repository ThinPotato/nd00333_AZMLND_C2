# Project 2
## Overview
This project demonstrates the process of deploying an Auto-ML model both manually and via an Azure pipeline. Additionally, we explore the details of the deployment via swagger as well as testing endpoints outside of the network.
## Architectural Diagram

```mermaid
  graph LR
  mlm(create Auto-ml model)
  d(deploy best model)
  nl(enable logging)
  ce(consume endpoints)
  mlm-->d-->nl-->ce
```

## Improvements
This project could be improved by allowing autoML to run for longer ensuring a better model is found. 

## Screenshots

### Step 2a: Register dataset
dataset is registered and available for use
![](https://github.com/ThinPotato/nd00333_AZMLND_C2/blob/master/sample_screenshots/Untitled15.png)

### Step 2b: Expirement Completed
Experiment has been completed, meaning the best model exists and can be further developed upon.
![](https://github.com/ThinPotato/nd00333_AZMLND_C2/blob/master/sample_screenshots/Untitled14.png)

### Step 2c: Demonstrating best model
Here, you can see the best model I was referring to in step 2. In this case, it is VotingEnsemble
![](https://github.com/ThinPotato/nd00333_AZMLND_C2/blob/master/sample_screenshots/Untitled13.png)

### Step 4a: Enable application insights
In this step I enabled application insights via python as seen through the valid URL.
![](https://github.com/ThinPotato/nd00333_AZMLND_C2/blob/master/sample_screenshots/Untitled12.png)

### Step 4b: Logs example
Here, you can see my logs capturaing data after hooking in through the newly created insights URL.
![](https://github.com/ThinPotato/nd00333_AZMLND_C2/blob/master/sample_screenshots/Untitled11.png)

### Step 5a: Swagger example
Here, you can see swagger running on my localhost. I've included HTTP API methods and responses.
![](https://github.com/ThinPotato/nd00333_AZMLND_C2/blob/master/sample_screenshots/Untitled8.png)

### Step 6a: Endpoint.py running
Here, you can see the endpoint.py script running against the API in swagger. The response we are expecting is in JSON and is the result of running this example through our best model
![](https://github.com/ThinPotato/nd00333_AZMLND_C2/blob/master/sample_screenshots/Untitled7.png)


### Additional screenshots demonstrating setup infrastructure

![](https://github.com/ThinPotato/nd00333_AZMLND_C2/blob/master/sample_screenshots/Untitled6.png)
![](https://github.com/ThinPotato/nd00333_AZMLND_C2/blob/master/sample_screenshots/Untitled5.png)
![](https://github.com/ThinPotato/nd00333_AZMLND_C2/blob/master/sample_screenshots/Untitled4.png)
![](https://github.com/ThinPotato/nd00333_AZMLND_C2/blob/master/sample_screenshots/Untitled3.png)
![](https://github.com/ThinPotato/nd00333_AZMLND_C2/blob/master/sample_screenshots/Untitled2.png)
![](https://github.com/ThinPotato/nd00333_AZMLND_C2/blob/master/sample_screenshots/Untitled1.png)
![](https://github.com/ThinPotato/nd00333_AZMLND_C2/blob/master/sample_screenshots/Untitled.png)

## Video demo
https://imgur.com/G2giBu1
![](https://imgur.com/G2giBu1)
