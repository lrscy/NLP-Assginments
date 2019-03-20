# Problem 4

## Usage

### Environment

- [Jupyter](https://jupyter.org/)
- [Python3](https://www.python.org/downloads/)

### Packages:

- nltk
- gensim
- readability
- numpy
- pandas
- sklearn
- scipy

You can find and install them by [PyPI](https://pypi.org/) and [Conda](https://conda.io/en/latest/).

### How to run

#### Simple run

To run the code, you need to open it in Jupyter and click the "Run All" in "Cell" label.

Notes: "Run All" will cost you about two hours on Intel i7 4th Gen.

#### Run on custom

If you want to run each subproblem, you can find and just run corresponding codes which will call
corresponding functions. For example, for problem 4.1.1, you can find codes in a cell:
``` Python
model_4_1_1 = problem4_1_1_train( data_train, stop_words, word2vec )
problem4_1_1_test( data_test, model_4_1_1, stop_words, word2vec )
```
All you need to do is to run it.

### Configuration

#### Stanford parser

For stanford parser, I choose to use an old version since new version cannot run on my computer.
If you would like to shift to new version, feel free to modify the code and try it :)

If you need to change environment parameters of the parser, follow the instruction on [stackoverflow](https://stackoverflow.com/a/22269678/4915449).

#### Corpus

To change the corpus, you need to modify following codes:
``` python
data_train = pd.read_excel( "Data/Train_Data.xlsx", sheet_name = "Sheet1" )
data_test  = pd.read_excel( "Data/Test_Data.xlsx", sheet_name = "Sheet1" )
```
You need to change path to position that your corpus saves.

To change language, you need to modify following codes and check the support of nltk:
``` python
stop_words = set( nltk.corpus.stopwords.words( "english" ) )
```

## Contributor

**Ruosen Li** | Master student | College of Engineering | Northeastern University
