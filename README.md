# Web Traffic Forecasting

This capstone project was a completed as a part of Udacity's Machine Learning Nanodegree Course. 

Companies such as Google are interested in having models which can predict web traffic to certain websites potentially for better resource distribution and ad placements. This project is based on a competition floated by Google on Kaggle.com about a year ago. The objective is to explore the web traffic project and create a time-series model which can predict web traffic for hundreds of wiki articles. 

Forecasting future events is a valuable many institutions such as stock markets, online sellers and advertisers. Forecasting web traffic is one of the most challenging problems the data has not just strong temporal effects but also dependencies on current events which are difficult to capture. 

The goal of the project is to predict the web traffic on the Wikipedia based on previous views for hundreds of wiki articles. Exploratory analysis will be performed on the dataset to find relevant information. A dataset will also be split and merged to find total daily views for each language. There will be two types of predictions made:
1.	Prediction for daily views for every page; and, 
2.	Prediction for daily views by language.
For forecasting, the dataset will be divided into a training set and testing set and validation set. The final prediction will be made for about a month (50 days). The quality of the predictions made by the model will be evaluated using Root Mean Square Error (RMSE).


## Getting Started

### Files needed

original proposal: Proposal.pdf

final project report: Project report.pdf

Jupyter Notebook: WebTrafficExploration.ipynb

html export of the Jupyter Notebook: WebTrafficExploration.html

### Prerequisites

* Python 3

* Jupyter notebook

* The following libraries need to be imported 

```
import numpy as np # linear algebra

import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)

import os

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

import re

from sklearn.metrics import mean_squared_error

from statsmodels.tsa.holtwinters import ExponentialSmoothing

from math import sqrt
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
