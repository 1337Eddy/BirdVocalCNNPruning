# BirdVocalCNNPruning

This project relates to my bachelor thesis. It is about pruning of CNNs which are used for detection of bird vocals.

I recommend to use Jupyter Notebook of the Anaconda Navigator to run the project.

Step 1: clone the repository
```
git clone git@1337Eddy/BirdVocalCNNPruning.git
```

Step 2: install dependencies
```
cd BirdVocalCNNPruning
pip install -r requirements.txt
```

Step 3: Donwload data from https://www.kaggle.com/c/birdclef-2021/data and extract the birdclef-2021 folder in the main directorie of the project

Step 4: Run the file Prepare_Data.ipynb in Jupyter notebook
This takes a while. The directory working/ is created and the soundfiles are extraced in 5 second sliced spectrogramms
