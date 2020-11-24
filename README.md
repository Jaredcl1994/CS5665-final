# Final Project - CS5665
## Jared Lambert

## Data
I'm using the volcanic eruption prediction dataset. The data consists of 10 minutes worth of sensor data for a set of volcanoes. 

## Goal
The end goal of the competition is to accurately predict how much time until the volcanoe will erupt. 

## Method
My plan is to use a deep neural network that takes a sensor reading for every sensor reading of the ten minutes worth of data. If that layer is too big, I may limit it to the most recent data, or I may take samples of the data to reduce resolution. 

### baseline
The baseline method will be a simple linear regression.

### other methods
I will try a convolutional neural net and a pretrained neural net. 
