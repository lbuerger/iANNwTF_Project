# iANNwTF_Project
Final project for the iANNwTF course in 2020/2021 university of osnabrueck tackling the topic of future crop yield predictions using a CNN architecture

## How to run
All needed packages are contaied in the `ann_proj.yaml` and can be installed via `conda env create -f ann_proj.yaml`.
When all data is pulled the **crop_yield.ipynb** containing all the code can be run.
In the second codeblock the boolean `run_on_colab` should be set to `True` or `False` depending on the used environment.

The training takes ~10 mins per epoch and can be interrupted to instead use the pre-trained model `ModelX1` 
