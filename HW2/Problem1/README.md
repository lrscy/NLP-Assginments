# Problem 1

## Usage

### Environment

- [Java](https://java.com/download/)
- [Jupyter](https://jupyter.org/)
- [Python3](https://www.python.org/downloads/)

### How to run

#### Simple run

To run the code, you need to open it in Jupyter and click the "Run All" in "Cell" label.

On AWS EC2 p2.xlarge environment with 4 vCPU, "Run All" may spend more than three hours.

#### Run on personal configuration

If you have not extracted proper sentences from files, you need to call functions below first:

```Pthon
filesName = getFilesName( "data/corpus/" )
contents = getContents( filesName )
writeContents( contents )
```
All extract sentences will be extracted to file "save/sentences.txt". The whole process
time on sample data (in "data/courpus/") will not exceed 5 seconds.

If you already have preprocessed files, firstly you need to call:
```Python
filesName = getFilesName( "data/corpus/" )
```
to get files name and run corresponding function of problem 1.1, 1.2, 1.3 in main function
seperately. The only parameter you need to change is the file path when calling those functions.

If you want to change save filename or others parameter, please follow notes in code and modify
corresponding path or parameters.

## Contributor

**Ruosen Li** | Master student | College of Engineering | Northeastern University