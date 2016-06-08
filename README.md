# NegNN (Neural Network for Automatic Negation Detection)

The code implements a feed-forward NN (```/feed_forward```) and a BiLSTM(```/bilstm```) to perform automatic negation scope detection. 

## Data
Training, test and development data can be found in the ```/data``` folder.
For training, development and initial testing, we used the data released for the [*SEM2012 shared task](http://www.clips.ua.ac.be/sem2012-st-neg/); please refer to the shared task and related papers for information regarding the annotation style.
Additional test data extracted from Simple Wikipedia is available in ```/data/test/simple_wiki```. The data was manually annotated following the guidelines released during the *SEM2012 shared task. Please refer to the .pdf file for ulterior information.

## Dependecies
- Tensorflow (tested on v. 0.7.1)
- scikit-learn (tested on v. 0.17.1)
- numpy (tested on v. 1.11.0)

## Train
To train the model 

