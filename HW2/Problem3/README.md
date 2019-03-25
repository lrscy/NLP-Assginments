# Problem 3

## Usage

### Environment

- [Jupyter](https://jupyter.org/)
- [Python3](https://www.python.org/downloads/)

### Packages

- sklearn
- gensim
- nltk
- numpy

You can find and install them by [PyPI](https://pypi.org/) and [Conda](https://conda.io/en/latest/).

### Notes

All outputs are saved in "save" folder. You can also find them in Jupyter notebooks in each
sub-problem's folder.

### Before run

Before running, please read and follow the README file in Data folder.

### How to run

To run the code, you need to open it in Jupyter and click the "Run All" in "Cell" label.

On AWS EC2 p2.xlarge environment with 4 vCPU, "Run All" may spend more than five hours and a half.

#### Configuration

If you want to change the position of corpus, you need to modify following codes "main" function:
``` python
posFilesName  = getFilesName( "Data/train/pos/" )
negFilesName  = getFilesName( "Data/train/neg/" )
testFilesName = getFilesName( "Data/test/" )
```

Also you need to configure your own path of bin file of word2vc. Corresponding code is:
``` python
w2vModel = gensim.models.KeyedVectors.load_word2vec_format(
                "Data/GoogleNews-vectors-negative300.bin", binary = True )
```

## Contributor

**Ruosen Li** | Master student | College of Engineering | Northeastern University
