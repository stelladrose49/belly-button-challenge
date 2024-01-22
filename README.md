# belly-button-challenge

<img width="1392" alt="Screenshot 2024-01-21 at 9 13 52 PM" src="https://github.com/stelladrose49/belly-button-challenge/assets/141170388/d9889de0-b618-41b9-a97b-c1a3fc88db63">


In this project, I successfully utilized the D3 library to read the samples.json data from a provided URL. I implemented a dynamic dashboard that includes a horizontal bar chart showcasing the top 10 Operational Taxonomic Units (OTUs) for an individual. The bar chart uses sample_values as values, otu_ids as labels, and otu_labels as hovertext.

Furthermore, I created a bubble chart to visualize each sample, utilizing otu_ids for the x values, sample_values for the y values, sample_values for marker size, otu_ids for marker colors, and otu_labels for text values.

To enhance user interaction, I implemented a dropdown menu that allows users to select different samples, updating all plots and displaying relevant sample metadata. The metadata includes key-value pairs from the metadata JSON object, providing insights into the individual's demographic information.

As a finishing touch, I deployed the interactive dashboard to GitHub Pages for easy access. The repository reflects a well-maintained structure with regular commits and a comprehensive README.md file.

Additionally, I tackled the advanced challenge by adapting a Gauge Chart to illustrate the weekly washing frequency of the individual. The gauge chart dynamically updates whenever a new sample is selected, providing an insightful visualization of hygiene practices.

Overall, this project showcases my proficiency in data visualization, interactivity, and effective deployment practices.
