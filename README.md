# D3-challenge
Matthew Richtmyer | 21 March 2020

## Trends VS Demographic Data
In this project, I used D3 JS to visualize data showing the relationship between median age and proportion of smokers across states in the US. 

## Pseudo Code
- Declare svg height, width, and spatial orientation 
- Load data in d3 using the d3.csv function.
  * Convert all relevant string data to numeric data types
  * Create axis using the scaleLinear function and orient them in the chart group object. Add labels to these axis. 
  * Create circles for each coordinate. Fill these circles with corresponding state abbreviation
  * Add tooltip functions
    - Create HTML code for mouseover
    - Remove HTML during mouseout
    
## Instructions
Clone this repo, and click "Go Live" on the index.html file using VS Code to render this locally. 

## Sample Screen Shot
![](https://github.com/mrichtmyer/D3-challenge/blob/master/assets/images/Screen%20Shot%202020-03-21%20at%203.14.32%20PM.png)
