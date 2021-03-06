# dl_experiments
Simple Deep Learning Experiments

Each directory contains a simple deep learning experiment.  See the subdirectories for explanations of what the experiments do.

## Installation instructions

1.  Install Keras (https://keras.io/#installation).  This requires installing either Theano or Tensorflow (explained in Keras documentation).

2.  Install ROOT (https://root.cern.ch/downloading-root) with python support.

3.  Check the code out from github:
```
git clone https://github.com/klannon/dl_experiments.git
```

## Using on CRC

Keras is installed on the CRC.  To access it, do the following on a CRC machine:
```
module load python
module load root
```

When you run Python, you'll find Keras (currently only with Theano backend) is installed.  Then you just have to clone the git repo to get going.
