# Generate TV Scripts

Generating a script for a Moe's Tavern scene using a recurrent neural network with long short term memory (LSTM) cells. The dataset is a subset of [this dataset](https://www.kaggle.com/wcukierski/the-simpsons-by-the-data), and includes scenes from Moe's Tavern from 27 seasons.

The aim of this project is generate a new Simpsons's script based on existing script data using recurrent neural networks, and go through the process of building and tuning one in TensorFlow.

### Files

[Jupyter Notebook](https://github.com/hparik11/Generate_TV_Scripts/blob/master/tv_script_generation.ipynb)

### Hyperparameters

Hyperparameter  | Number |
--------------- | ------ |
Epochs          | 100     |
Batch size      | 500    |
RNN size        | 256    |
Embedding size  | 300      |
Sequence length | 25     |
Learning rate   | 0.005  |


### Let's Have Some Fun

Check out the output in a professionally stylized script format! ([Click here](https://github.com/nehal96/Simpsons-Script-Generation/blob/master/Simpson's%20Script%20-%20Queen's%20Elizabeth.pdf) for PDF)
