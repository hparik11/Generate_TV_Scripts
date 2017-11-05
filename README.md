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

### Sample Script Generated:

moe_szyslak:(uneasy) oh, i can't wait till you guys get to uh...
moe_szyslak: so, uh, you still want to go out?
maya:(shrugs) that's why i'm here to you guys, mr. smithers, our lives amount.
moe_szyslak: hey, hey, hey, hey! you said, you saved me.
marge_simpson:(flustered) oh, no, no. chicks do not like finding out they're being spied on a day...
homer_simpson:(frightened) denser?!
marge_simpson: damn straight, my eye! ow! ow! ow! get it out!
moe_szyslak:(realizing, to phone) it's you...
moe_szyslak:(nervous) you gotta be kiddin' me. like what?
carl_carlson:(nods) yeah. that's why i wrap my plums in tin foil.
seymour_skinner: oh my god, i've never felt so i'm looking for--
homer_simpson:(morose) oh, what'll i do, moe?
moe_szyslak: well, i assume i'm not the

