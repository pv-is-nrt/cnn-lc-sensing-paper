Welcome to the code repository for the paper

# A Liquid Crystal-based Biomaterial Platform for Rapid Sensing of Heat Stress using Machine Learning

*Authors: Prateek Verma, Elizabeth Adeogun, Elizabeth S. Greene, Sami Dridi, Ukash Nakarmi, Karthik Nayani*

> Link to the paper: to be added later  
> Link to the preprint: [https://arxiv.org/pdf/2405.15068](https://arxiv.org/pdf/2405.15068)

This repository contains the necessary code files to run experiments, evaluations, analysis, process and generate data for the study pertaining to the research paper. Specific details for files/folders in this repo are provided below.

Please feel free to contact me with any questions.


## Experiment Notebook.ipynb
An example notebook to run a machine learning experiment for this study. The notebook contains all necessary instructions within. Interested researchers should start with this file.


## E 00009 strained unstrained chicken unpolarized
An example output directory that contains that particular experiment's notebook, a description file, training history, plots for accuracy, loss, confusion matrices, and ROC curves, trained model h5 file, trained model weights visualization, and prediction visualization for each CNN layer.  
Each experiment output directory contained similar files and folders.


## Model architectures
This folder contains all the tensorflow model architectures used in the study. Researchers can use these models to run their own experiments.


## Data

This repository DOES NOT contain the data (images) used in the study due to their large size. Researchers can specify their own data to run their own experiments. Or contact me for access to the data used in the study.  
The image files should be organized in the following directory structure to be able to readily use the Notebook with minimal changes:
```
- data folder
    - test
        - class1
            - image1.jpg
            - image2.jpg
            - ...
        - class2
            - image1.jpg
            - image2.jpg
            - ...
        - ...
    - train
        - similar to test structure
    - val
        - similar to test structure
```