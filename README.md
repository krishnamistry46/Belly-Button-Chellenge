# Belly-Button-Chellenge
Module 14- Javascript Belly-Button-Challenge
# Project Overview
This project delves into an interactive exploration of microbial data from various individuals, leveraging the D3.js library to parse and visualize information from a comprehensive JSON dataset. The initiative aims to uncover the top Operational Taxonomic Units (OTUs) present in individuals, employing dynamic visualizations like horizontal bar charts and bubble charts to represent the complexity and richness of the data. Through an intuitive interface featuring dropdown menus and responsive charts, users can navigate the dataset to gain insights into the microbial communities within each sample. The project also includes visualizing demographic metadata, providing context to each dataset explored. Hosted on GitHub Pages, the project invites users to engage with the data interactively, highlighting the capabilities of web-based data visualization tools and enabling a deeper understanding of microbiological ecosystems through data analytics.

# Deployment
Explore the fascinating world of microbial ecosystems with our interactive dashboard: BioD3: Visualizing Microbial Ecosystems.

# Data
The data for this project originates from a study conducted by Hulcr, J. et al. (2012), titled "A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable." This research reveals the diversity and predictability of bacterial ecosystems residing in human belly buttons, based on samples collected from a diverse group of participants. Accessible through the Rob Dunn Lab's website, the study offers a comprehensive exploration into the microcosm thriving within our navels, highlighting the intricate factors influencing the composition of these bacterial communities. Our interactive dashboard leverages this dataset to visualize and understand the bacterial diversity present in different individuals' belly buttons, illustrating the broader implications of microbial biodiversity on human health and ecology.

# Technologies Used
- D3.js: For data manipulation and binding to DOM elements.
- Plotly.js: For creating interactive visualizations including bar charts, bubble charts, and gauge charts.
 -Bootstrap: For responsive design and layout.
# Features
# Horizontal Bar Chart: Displays the top 10 OTUs found in the selected individual from the dropdown menu.

- Values: sample_values
- Labels: otu_ids
- Hovertext: otu_labels
# Bubble Chart: Visualizes each sample.

- X values: otu_ids
- Y values: sample_values
- Marker size: sample_values
- Text values: otu_labels
- Demographic Information Panel: Shows demographic details of the selected individual as key-value pairs.

# How to Use
Select a Test Subject ID Number from the dropdown menu to update the visualizations with data specific to that individual.
Hover over the charts to view additional details about the bacteria cultures and their frequencies.
This project aims to provide an engaging and informative experience for exploring microbial biodiversity through interactive data visualization tools.
