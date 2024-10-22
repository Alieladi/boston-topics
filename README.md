# Topic modeling on Boston neighborhood overviews
## Installation
The code runs on Python 3.

Requirement libraries: NumPy, Pandas, Scikit-learn, Plotly and Spacy.
## Project Motivation
This project aims to extract major topics in the neighborhood overviews, to address questions such as:
- Which neighborhoods are more described as quiet, safe and residential?
- Which neighborhoods are strongly claimed to have restaurants, bars and shops?
- Which neighborhoods are claimed nice to go on a walk for having green space, rivers, etc.?

## Method and Results
In summary, we find 5 separate topics representing different characteristics about neighborhoods. Each characteristic helps answer one of our questions by calculating for each neighborhood the proportion of overviews involving that characteristic.
For example, Longwood Medical Area and Roxbury have overviews of which a high proportion is describing them as quiet, safe and residential.

The Full analysis is published on the Medium post: https://medium.com/@alieladi/explore-boston-neighborhoods-with-airbnb-data-db7a81558fad

## File Descriptions
`Airbnb-overview-topics.ipynb`: notebook related to the analysis

`listings.csv`: dataset of listings from https://www.kaggle.com/airbnb/boston
