# belly-button-challenge
Belly Button Biodiversity

The coolest study of biodiversity on the human body on the planet!
Build an interactive dashboard to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.
The belly button is one of the habitats closest to us, and yet it remains relatively unexplored. In January 2011, we launched Belly Button Biodiversity to investigate the microbes inhabiting our navels and the factors that might influence the microscopic life calling this protected, moist patch of skin home. In addition to inspiring scientific curiosity, Belly Button Biodiversity inspired conversations about the beneficial roles microbes play in our daily lives.
![image](https://user-images.githubusercontent.com/12514249/229164494-a21ff24c-9473-4dd1-8fe3-63703e7c107c.png)

we revealed that belly buttons are indeed a jungle of microbial diversity, having detected over 2300 species in those 60 navels! Just eight of those species – we called them oligarchs – were frequent and abundant across the individuals sampled (they were present in more than 70% of people); the remaining species were quite rare, often appearing in just a single navel.
This paper left us with a head-scratching puzzle: We could predict what species would be most common in a room full of belly buttons (the oligarchs!), but we lacked the ability to predict what species would be present at the level of the individual.

The investigated factors like age, sex, ethnicity, innie vs outie, and frequency of washing – yet none of the factors explained differences in the number and kinds of bacteria we found in a particular person.


https://ktaware.github.io/belly-button-challenge/

# Instructions
Complete the following steps:

Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.
# bar Chart
Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

Use sample_values as the values for the bar chart.

Use otu_ids as the labels for the bar chart.

Use otu_labels as the hovertext for the chart.

![hw01](https://user-images.githubusercontent.com/12514249/216697904-aeece908-ac77-4f2e-bca3-c7b7739daaeb.jpg)

# Bubble Chart
Create a bubble chart that displays each sample.

Use otu_ids for the x values.

Use sample_values for the y values.

Use sample_values for the marker size.

Use otu_ids for the marker colors.

Use otu_labels for the text values.
![bubble_chart](https://user-images.githubusercontent.com/12514249/216698830-a674e3a1-8a4f-44a4-9996-d4f79c3a7211.jpg)


# Display the sample metadata, i.e., an individual's demographic information.
Display each key-value pair from the metadata JSON object somewhere on the page.
![hw03](https://user-images.githubusercontent.com/12514249/216698899-3cef4771-f128-4cc7-b2a8-7267482be287.jpg)


hw
# Update all the plots when a new sample is selected. An example dashboard is shown as follows:

![hw02](https://user-images.githubusercontent.com/12514249/216698935-5be231ec-ee23-47e0-8a79-d259a1477a5b.jpg)
hw
Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file

Advanced Challenge Assignment (Optional with no extra points earning)
The following task is advanced and therefore optional.

Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/ Links to an external site.to plot the weekly washing frequency of the individual.

You will need to modify the example gauge code to account for values ranging from 0 through 9.

Update the chart whenever a new sample is selected.

# Weekly Washing Frequency Gauge

![gauge](https://user-images.githubusercontent.com/12514249/216698961-2348be2e-c749-4c07-94ef-cfefef2c8f89.jpg)


Hints
Use console.log inside of your JavaScript code to see what your data looks like at each step.

Refer to the Plotly.js documentation Links to an external site.when building the plots.


# References
Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/Links to an external site.

© 2023 e
