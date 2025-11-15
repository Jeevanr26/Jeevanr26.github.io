Chart 1:
  
  My first visualization is a collection of the fifteen Illinois State agencies that have the highest amount of buildings in the Illinois Building Inventory dataset.
To create this visual summary, I aggregated the total number of records per agency and filtered that result with the top fifteen agencies so that the chart will focus 
on the main property holders instead of agencies with a few buildings.The data is shown using a horizontal bar chart, in this chart, the bar length encodes count():Q
and the y-axis lists Agency Name:N sorted in descending order. To distinguish each of the agencies I used different colors. The chart also includes a hover based
interaction that highlights the bar under the cursor while dimming the others.This feature helps the user isloate an agency within the chart.

Chart 2:

My second visualization is a scatterplot that shows the relationship between when a building was acquired and how big it is. The plot uses a point to represent each
singular building. Before making the chart I had prepare the data by cleaning and converting the 'Year Acquired' and 'Square Footage' columns to numeric values, I also
removed all the null values. This plot has Year Acquired on the X-axis and Square Footage on the Y-axis, it also has color mapped to agency name. This chart's interactive
feature is a legend based selection that allows the users to click an agency and only highlight their buildings. I added these interactions so it would be easier for the
user to spot patterns in building size.


Dataset: Illinois Building Inventory Dataset: (https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv)
Python Notebook: (https://github.com/Jeevanr26/Jeevanr26.github.io/blob/main/HwFive.ipynb)
