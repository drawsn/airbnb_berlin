# Airbnb Berlin Listings analysis

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code should run with no issues using the Python versions 3.* and the Anaconda distribution.

The python libraries used are:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Sklearn

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Airbnb data from Berlin to better understand:
1. How does cancellation policy influence utilization?
2. What factors heavily influence review scores?
3. How does the neighborhood influence the listing price? How well can we predict the price of a listing using a linear ML model?

The analysis was done with the help of the ipython notebook included in this repository. The data source for Berlin 11-07-2019 was downloaded from http://insideairbnb.com.

The results are summarized in a medium blog post you can find [here](https://medium.com/@a.hampersberger/airbnb-berlin-first-steps-into-data-science-with-python-pandas-ba26026edf94?source=friends_link&sk=4e1a7e427a02d159e48fbe4a5b432ca2)

## File Descriptions <a name="files"></a>

airbnb_berlin.ipynb > notebook to showcase work related to the above questions. Markdown cells were used to assist in walking through the thought process for individual steps.

listings.csv.gz > The data source used in the analysis

README.md > This file

## Results<a name="results"></a>
The analysis showed that stricter cancellation policies tend to increase the utilization of a listing. Another finding was, that the review scores were not influenced heavily by any specific feature, despite communication beeing an important factor. Although the price is only influenced a little by neighborhood, there is a tendency to be seen. Lastly the machine learning model did not predict the price levels too well and might need some reworking in the future.

As mentioned above, the main findings of the analysis can be found in a medium blog post available [here](https://medium.com/@a.hampersberger/airbnb-berlin-first-steps-into-data-science-with-python-pandas-ba26026edf94?source=friends_link&sk=4e1a7e427a02d159e48fbe4a5b432ca2).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit to Insideairbnb for the data. You can find the Licensing for the data at the link available [here](http://insideairbnb.com/get-the-data.html).
