# Web Visualization Dashboard 

## Background

Data is more powerful when we share it with others!

A website is created by using weather data (Resources/cities.csv).

The website includes the following:

* A [landing page](#landing-page) containing the following elements:

  * An explanation of the project

  * Links to each visualizations page with a sidebar containing preview images of each plot.

* Four [visualization pages](#visualization-pages), stored in the `visualizations` folder, each with the following elements:

  * A descriptive title and heading tag.

  * The plot or visualization for the selected comparison (latitude vs: max temperature, humidity, cloudiness, or wind speed).
  
  * A paragraph describing the plot and its significance.

* A ["Comparisons" page](#comparisons-page) that does the following:

  * Contains all of the visualizations on the same page so they can easily be compared with each other.

  * The data comes from exporting the `.csv` file as HTML or by converting it to HTML. Tools used: Pandas. 
  
At the top of every page, the website has a navigation menu with the following elements:

* Name of the site on the left of the navigation bar, allowing users to return to the landing page from any page.

* Contains a dropdown menu on the right of the navigation bar, named "Plots," to provide links to each individual visualization page.

* ProvideS two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.

* It is responsive (using media queries). 

Finally, the website is deployed to GitHub Pages.
