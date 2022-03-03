# python-word-count-beam
- Here are the steps and commands to implement word count using python 

## Checking the Python version
`python --version`

## Installing pip
`pip --version`

## Upgrade pip version
`PS> python -m pip install --upgrade pip`

## Creating a virtual environment
`PS> python -m venv C:\path\to\directory`

## Activating a virtual environment
`PS> C:\path\to\directory\Scripts\activate.ps1`

## Install the latest Python SDK from PyPI
`PS> python -m pip install apache-beam`

## Copy these files into your local
- [wordcount.py](https://github.com/TejaswiNallavolu/python-word-count-beam/blob/main/wordcount.py)
- [sample.txt](https://github.com/TejaswiNallavolu/python-word-count-beam/blob/main/sample.txt)

## Executing the pipeline
`python -m apache_beam.examples.wordcount --input /path/to/inputfile --output /path/to/write/counts`


- [References](https://beam.apache.org/get-started/quickstart-py/)
