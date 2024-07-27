# pdf-sanitize
Get rid of unwanted JavaScript and attachments in a PDF file

### Dependencies
[PyPDF 4.x](https://pypi.org/project/pypdf/)

### How to run
1. Install PyPDF
```shell
$ pip install -r requirements.txt
```
2. Run
```shell
$ python main.py inputfile.pdf outputfile.pdf
```

### How it works?
It rebuilds the PDF from scratch, discarding any JavaScript embedded in actions and in the document root. Attachments are restored only if the user requests that when prompted.
