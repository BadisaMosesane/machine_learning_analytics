# DS_ML: Machine Learning Jupyter notebooks 

This repo is for machine learning algorithms for analyzing different datasets and to be used for training DS ML newbies.
Ranging from simple linear regression, Classification, K-Nearest Neighbour and Decision trees and Support Vector Machines.       

## Key features

- Interactive data visualization
- Display of key features
- Step by step workflow for predictions
- Chatbot for user engagement on data and concepts

![](data/dashboard.png)

## Getting Started

First create a virtual environment with conda or venv inside a temp folder, then activate it.

```
virtualenv venv

# Windows
venv\Scripts\activate
# Or Linux
source venv/bin/activate

or on macos
conda create --name myenv
conda activate myenv

```

Clone the git repo, then install the requirements with pip

```

git clone https://github.com/BadisaMosesane/machine_learning
cd machine_learning
pip install -r requirements.txt

```

Run the app

```
cd machine_learning
python app.py

```

## Sofware Used
- Plotly Dash
- Pandas
- Numpy
- Scikit-learn

## Issues
* chatbot redirects: will like to do trigger within the same page 
* Predictions integrations
* Enhance UI

## Contributions

We welcome contributions to this work, to contribute simply do a Pull Request on the [repo](https://github.com/BadisaMosesane/machine_learning)

## License
This work will be openly published under Apache 2.0

## Authors
- Badisa Mosesane

## Built With

- [Dash](https://dash.plot.ly/) - Main server and interactive components
- [Plotly Python](https://plot.ly/python/) - Used to create the interactive plots
- [IBM Watson Assistant](https://www.ibm.com/cloud/watson-assistant) -  for  developing the edu-chatbot

