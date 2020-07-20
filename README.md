# Coursera Capstone Project
Capstone Project Final Report - Mohammad Qara
Choosing best location to rent an ampartment near a sport gym and school a mall market in Jeddah, Saudi Arabia

1. Background
My cleint wants to rent an apartment and he needs that apartment to be close from a sport gym, school and a shopping mall and he wants a location on the centert of the city of Jeddah and he doesn't know where he sould go where to the center of Jeddah, so based on our experience in data science we got hired to help him to decide what is the suitable place to rent that apartment.

2. Description of the problem
The problem is to help my client who are planning to rent an apartment near a gym, school and a shopping mall in city of Jeddah, Saudi Arabia and he wants to be close to the center of Jeddah so based on that, we as a data scientist will fint the best place that mathes his criterias.

3. Data
We are going to import our data from Forsquare using Forsquare free API, so in we are going to call the api whith spicified argument like specifying the place as a sport gym, school, mall and we are putting a specified raduis for highlighted places in Jeddah. And that places must be near the center of Jeddah, and that places are going to be gathered and cleaned by the the data science team.

4. Methodology
1. Find the location of gyms, school, malls near center of Jeddah with Foursquare API as JSON.
2. Analyze the JSON file to a Pandas Dataframe.
3. Plot the three types of location on the map.
4. Convert each cluster of location and plot it in a scatter plot.
5. Find the centeroid of each cluster.
6. Find the final centroid of the last three centroids from the three cluster.
7. Plot the final centroid on the map.
5. Results
Plot the three types of location on the map.
img

Convert each cluster of location and plot it in a scatter plot and find the centroid
Gyms scatter plotimg

School scatter plotimg

shopping mall scatter plotimg

Find the final centroid of the last three centroids from the three cluster.
img

Plot the final centroid on the map
img

After calculating the centroids of the three types, we got that coordenates (21.579360241745352, 39.15923497751423) and this area represent the center of the three clusters of locations in jeddah.
6. Disscussion
after seeing the results, we noticed that the the final coordinates is located in a very great area which connects the with two main roads in Jeddah, Sari street and Madinah road street.. and this gives a good and fast access to the areas we need to reach

7. Conclusion
based on this project, we figured out that the data analysis is a very interesting feild and very important department in each company, data need to be collected for any future analysis, and trough this project. we see how to import places from the FourSquare API and how to convert it to Pandas dataframe and finally visualize it trhough Folium.
