There are two ways to interact with the code:

1. You can play with the model:
  - clone the repo
  - download the final model to the model directory with this [link](https://drive.google.com/file/d/1AFDcpQInLZNXlMAKW-chAiqStRvQUJTz) (~120MB)  
  - play with the model in the evaluation.ipynb (PLAYING WITH THE MODEL section)

 2. You can retrain the model:
  - clone the repo 
  - download the train.csv from [Kaggle competition page](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data) to the data directory
  - preprocess the data and produce train_pre.csv with the preprocessing.ipynb (this will also overwrite the tokenizer in the pickles directory)
  - run the learning.ipynb: import statements, definition of the functions (second cell), BASIC SETUP section and TRAINING AND SAVING THE FINAL MODEL section
