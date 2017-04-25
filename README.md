# Tensorflow Chat Bot
A chatbot using Tensorflow and Cornell Universities movie dialogue dataset. 
This is a tutorial of one of the videos by Sirajology 

## Dependencies:</br>
numpy </br>
scipy</br>
six</br>
tensorflow</br>

## Dataset:
https://www.cs.cornell.edu/%7Ecristian/Cornell_Movie-Dialogs_Corpus.html
Also, I prefered getting the dataset directly from 
https://github.com/suriyadeepan/datasets
and runnning suriyadeepan/datasets/seq2seq/cornell_movie_corpus/scripts/prepare_data.py
make sure you uncomment the last line of prepare_data.py in order to prepare your data. 
Then make sure to create a working_dir folder

## Usage:
To train the bot:
```
nano seq2seq.ini # edit so that mode is set to train like so
mode = train

python execute.py
```
To test the bot during or after training:
```
nano seq2seq.ini # edit so that mode is set to test like so
mode = test

python execute.py
```

## Some Clarification:
Note: Some of the files are taken from the examples folder of Tensorflow</br>
Prior to do anything:</br>
- make sure you have all dependencies downloaded and installed
- tensorflow setup properly (I am still getting an error) More info on that here https://www.tensorflow.org/install/
- you have all your datasets ready
- datasets are properly sorted (meaning they are in proper folders, otherwise you will be facing multiple issues as well) 
- it will take a very long time to train this bot on your personal computer, so leave it for a while.

## Next Steps:
Find more datasets and have it work on a specific set.


Many thanks to Siraj for his tutorials https://github.com/llSourcell
