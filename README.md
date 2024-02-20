# Project Description
Coronavirus disease 2019 (COVID-19) is an infectious disease caused by severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2). It was first identified in December 2019 in Wuhan, Hubei, China, and has resulted in an ongoing pandemic. As of 25 September 2020, more than 32.2 million cases have been reported across 188 countries and territories with more than 983,000 deaths; more than 22.2 million people have recovered.

---

# Content

- CHOROPLETH MAPS

  - Choropleth Map of World
  - Choropleth Map of Asia
  - Choropleth Map of Europe

- LINE CHARTS

  - Line Chart - Infection Rate of India
  - Line Chart - Death Rate of India
  - Line Chart - Recovery Rate of India

- SCATTER PLOTS

  - Scatter Plot - Confirmed v Active Case of India
  - Scatter Plot - Deaths v Recovered of India

- PIE CHARTS

  - Percentage of Total Deaths in 20 Most Affected Countries
  - Percentage of Total Recovered in 20 Most Affected Countries

- BAR CHARTS

  - Comparison of Total Tests in 10 Most Affected Countries
  - Comparison of Deaths/Million in 10 Most Affected Countries

- BUBBLE CHART

  - Bubble Plot for Total Cases v Total Deaths

- SUNBURST CHART

  - Sunburst Chart for Active Cases

- 3D PLOT

  - 3D Plot for Total Case, Total Deaths and Total Recovered


---

# Intro To Plotly

The Plotly Python library is an interactive, open-source plotting library that supports over 40 unique chart types covering a wide range of statistical, financial, geographic, scientific, and 3-dimensional use-cases. Now, We are going to analyse and find insights with this interactive Visualization Library.

- ***Choropleth Map***
    - A Choropleth Map is a map composed of colored polygons. It is used to represent spatial variations of a quantity. Below we show how to create Choropleth Maps using the Plotly Express 'px.choropleth'

    - **Choropleth World Map**



    - **Choropleth Continent Map**
 

- ***Line Plots And Sctter Plots***
   - With 'px.line', each data point is represented as a vertex 
(which location is given by the x and y columns) of a polyline mark in 2D space.
For Line Charts, We will see the trend of Infection Rate, Death Rate and Recovery Rate 
of India with respect to the Phases of the Nationwide lockdown.

  - **Line Plots**
      - *New Cases*:
   

      - *New Deaths*:
   
  - As we can see the plotted line plots.India had recorded 5,85,474 cases of COVID-19 and 17,412 deaths. The day's toll was the biggest surge in deaths since 2,003 fatalities were reported on June 16, with most of those numbers comprising earlier deaths confirmed during data reconciliation processes in Maharashtra and Delhi.

  - **Scatter Plots**

     - *Confirmed Active Cases*:
   

     - *Death and Recovery Cases*:
   


- ***Pie Charts***
    - A pie chart is a circular statistical chart, which is divided into sectors to illustrate numerical proportion.
In 'px.pie', data visualized by the sectors of the pie is set in values. The sector labels are set in names.

    - *Percentage of Total Deaths in 20 Most affected Countries*:


    - *Percentage of Total Recovered in 20 Most affected Countries*:
 

- ***Bar Charts***
    - With 'px.bar', each row of the DataFrame is represented as a rectangular mark. For Bar Charts we will be comparing the Total Tests and Deaths/Million of Top 10 Affected Countries.

    - *Comparison of Total Tests of 10 Most Affected Countries*:
 

    - *Comparison of Deaths/Million of 10 Most Affected Countries*:
 

    - *Comparison of Cases/Million of 10 Most Affected Countries*:
 

    - *Comparison of Tests/Million of 10 Most Affected Countries*:


- ***Bubble Charts***
    - A bubble chart is a scatter plot in which a third dimension of the data is shown through the size of markers. 
For other types of scatter plot, see the line and scatter page.

    - *Bubble Plot for Total Cases v Total Deaths of 50 Most Affected Countries*:


- ***SunBurst Chart***
    - Sunburst plots visualize hierarchical data spanning outwards radially from root to leaves. The sunburst sector hierarchy is determined by the entries in labels (names in px.sunburst) and in parents.
The root starts from the center and children are added to the outer rings. Let's Analyse Active Cases of Top 50 Countries here.

- *Sunburst Chart*


- ***3D-Plot***
    - Like the 2D scatter plot 'px.scatter', the 3D function 'px.scatter_3d' plots individual data in three-dimensional space.
Here Let's do it on Total Cases, Total Deaths and Total Recovered of 20 Most Affected Countries. Don't forget to move the 3D Plot

    - *3D Plot of Total Cases, Total Deaths and Total Recovered of Top 20 Affected Countries*
