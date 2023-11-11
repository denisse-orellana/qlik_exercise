# Case Study of CitiBikes in New York 

From [Taller en vivo de iniciación: Analizamos datos de Bike Sharing](https://www.youtube.com/watch?v=E7szrM2ndHY).

## Background

This project works with data from [CitiBikes](https://citibikenyc.com/system-data).

## Data Visualization with Qlik

### To make graphics we need:
* Metrics: Sum(Trips)
* Dimension: period

### 1. Replace gender names 

Replace gender names with the information from the official site.

<p align="left"><img width="100%" src="./images/qlik_0.png"></p>
<p align="left"><img width="100%" src="./images/qlik_1.png"></p>

### 2. Add a calculated field 

Add a new field with the age.

<p align="left"><img width="50%" src="./images/qlik__2.png"></p>
<p align="left"><img width="100%" src="./images/qlik_3.png"></p>

### 3. Create a new analysis from scratch

<p align="left"><img width="100%" src="./images/qlik_4.png"></p>

Trips ID by bicycle:
<p align="left"><img width="100%" src="./images/qlik_5.png"></p>

Trips ID by period:
<p align="left"><img width="100%" src="./images/qlik_6.png"></p>

Trips ID by age:
<p align="left"><img width="100%" src="./images/qlik_7.png"></p>

Trips ID by gender:
<p align="left"><img width="100%" src="./images/qlik_8.png"></p>

### 3. Advanced Tools

Use of maps for the longitude and latitude values from the estations:

<p align="left"><img width="100%" src="./images/qlik_9.png"></p>
<p align="left"><img width="100%" src="./images/qlik_10.png"></p>
