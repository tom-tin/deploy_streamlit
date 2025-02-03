# Deploy Streamlit

## Project Overview
This shows a simple example of how to deploy a simple ML model on to Streamlit. It is an adaptation from the source in the Reference section.
The changes I make compare to the source:
* Separate one single original python file "mymodel.py" into two: model.py handles data generation and model training. main.py handle the Streamlit interface and viz.
* During the run, I notice that a few imports has to be brought from the original mymodel.py into the model.py too. You cannot just leave all imports in main.py

## Installation
Instructions on how to install the necessary dependencies.

```sh
pip install -r requirements.txt
```

## Usage
Instructions on how to run the project.

```sh
python main.py
```

## Notebooks
Description of the notebooks included in the project.
* notebooks/exploration.ipynb: Initial data exploration and analysis

## Contributing
Guidelines for contributing to the project.

## License
Information about the project's license. 

## Reference
[How to Quickly Deploy Machine Learning Models with Streamlit ](https://machinelearningmastery.com/how-to-quickly-deploy-machine-learning-models-streamlit/)
