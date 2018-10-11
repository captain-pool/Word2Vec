## Tensorflow Implementation of Word2Vec
Network Architecture: CBOW
Output Vector Dimension: 128
How to execute:
1. Clone the repo and open the python notebook using Google Colab, (TO GET THE GPU)
If the code is desired to be run on local machine with no GPU/tensorflow-gpu, edit this line.
```python
with tf.device('/gpu:0'):
    #Codes here
```
to
```python
with tf.device('/cpu:0')
    #Codes here
```
2. Run the cells in the Jupyter environment
The last cell is meant to be run in Google Colab for downloading the pickled vector dictionary.
