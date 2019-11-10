# Portfolio - Yevgeny (Eugene) Bulochnik

## Table of Contents
* [Devops](#devops)
* [Full Stack](#full-stack)
* [Data Analysis and Viz](#data-analysis-and-vizualization)
    - [Medimap](#medimap) - Medicare reimbursement geomap
    - [AspCalc](#aspcalc) - ASP/CMS reimbursement calculator
    - [D3test](#d3test) - React d3 integration

# Devops
# Full Stack
# Data Analysis and Vizualization

### Medimap
Interactive Medicare charge/reimbursement geomap. A large CMS data set (over 10 million records) with historical data on provider charges and medicare reimbursement was manipulated using python and geomapped with the help of geocod.io. Django Rest Framework was used to develop a RestApi, while React with the help of leafletjs was used to create the map. 

<p align="center">
    <img src="https://github.com/yevgenybulochnik/web-assets/blob/master/medimap/medimap.gif">
</p>

### AspCalc
ASP dosing and reimbursement calculator. This calculator is generated using create-react-app and various python data analysis libraries. Data sets from CMS were manipulated and combined to create a single usable json file which feeds the calculator UI

<p align="center">
    <img src="https://github.com/yevgenybulochnik/web-assets/blob/master/aspcalc/aspcalc.gif">
</p>

### [D3test](https://github.com/yevgenybulochnik/d3test)
This repo is an example setup for [d3](https://d3js.org) integration for [react](https://reactjs.org). It allows for pannable, zoomable and resposive svg charts.

<img src="https://github.com/yevgenybulochnik/web-assets/blob/master/d3test/d3test.gif">
