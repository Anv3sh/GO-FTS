# A Simple Full-Text Search engine in Go

We are going to search a part of the abstract of English Wikipedia. The latest dump is available at 
[dumps.wikimedia.org](https://dumps.wikimedia.org/enwiki/latest/enwiki-latest-abstract1.xml.gz). As of today, the file size after decompression is 913 MB. The XML file contains over 600K documents.

## Steps to run:
```
$ go build -o GO-FTS.exe
$ ./GO-FTS.exe
```

