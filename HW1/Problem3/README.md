# Readme for problem 3

## Usage

### Environment

[Jupyter](https://jupyter.org/), [Python3](https://www.python.org/downloads/)

### How to run

To run the code, you need to open it in Jupyter and click the "Run All" in "Cell" label.

## Configuration

If you need to change file path, please change it in the second last cell. Here is the meaning of each parameter (they are also noted in previous cells):

In problem 3.1:
* trainDataPath: the path contains all train data. Default is "./gutenberg".
* encoding: the encoding of files in traindDataPath. Default is "Latin-1".
* savePath: the path to save language model. Default is "./lm".
* ratio: the propotion of real train files in trainingDataPath, others would be used as held-out data. Default value is 1, which means all files in trainDataPath would be used as real train data.

In problem 3.2:
* trainDataPath: the path contains all train data. Default is "./gutenberg".
* encoding: the encoding of files in traindDataPath. Default is "Latin-1".
* savePath: the path to save language model. Default is "./3_2".
* testDataPath: the path contains all test data. Default is "./test_data".
* ratio: the propotion of real train files in trainDataPath, others would be used as held-out data. Default is 1.

In problem 3.3:
* lmPath: the path contains all train data. Default is "./lm".
* encoding: the encoding of files in lmPath. Default is "Latin-1".
* savePath: the path to save language model. Default is "./3_3".
* testDataPath: the path contains all test data. Default is "./test_data".

## Contributor

**Ruosen Li** | Master student | College of Engineering | Northeastern University
