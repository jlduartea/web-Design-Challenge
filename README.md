# web-Design-Challenge

## Web Design Homework - Web Visualization Dashboard (Latitude)

## Background

We have to create a dashboard showing off the analysis we've done.

![Images/Index.PNG](Images/Index.PNG)

## Latitude - Latitude Analysis Dashboard with Attitude

For this homework I created a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting [weather data](Resources/cities.csv).

In building this dashboard, I createe individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations.I also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

The website must consist of 7 pages total, including:

* A Landing Page containing:
  * An explanation of the project.
  * Links to each visualizations page.
  ![Images/Landing Page](Images/Visualization.PNG)

* Four Visualization Pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
    ![Images/Max Temp](Images/MaxTemp.PNG)
    ![Images/Humidity](Images/Humidity.PNG)
    ![Images/Cloudiness](Images/Cloudiness.PNG)
    ![Images/Wind Speed](Images/WindSpeed.PNG)

* A Comparisons Page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
    ![Images/Comparison Page](Images/Comparisons1.PNG)

* A Data Page that:
  * Displays a responsive table containing the data used in the visualizations.
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. 
    ![Images/Data Page](Images/Data.PNG)

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
    ![Images/Navigation Menu](Images/PlotPopUp.PNG)

* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#Index) (notice the background color change).

### Screenshots

This section contains screenshots of each page that must be built, at varying screen widths. These are a guide; you can meet the requirements without having the pages look exactly like the below images.

#### Landing page

Large screen:
![Landing page large screen](Images/Index.PNG)

Small screen:
![Landing page small screen](Images/Index-sm.PNG)
￼

#### Comparisons page

Large screen:
![comparison page large screen](Images/Comparison.PNG)

Small screen:
![comparison page small screen](Images/Comparison-sm.PNG)

#### Data page

Large screen:
![data page large screen](Images/Data.PNG)

Small screen:
![data page small screen](Images/Data-sm.PNG)

#### Visualization pages

You'll build four of these, one for each visualization. Here's an example of one:

Large screen:
![visualize page large screen](Images/Visualization.PNG)

Small screen:
![visualize page small screen](Images/Visualization-sm.PNG)

#### Navigation menu

Large screen:
![nav menu large screen](Images/PlotsPopUp.PNG)

Small screen:
![nav menu small screen](Images/PlotsPopUp-sm.PNG)