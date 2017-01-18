+NOTE THIS WILL ONLY WORK IF YOU HAVE PYTHON 2.7 OTHERWISE refer to S3.md

## Synopsis

Script used to perform multipart uploads of large files to s3 bucket. You can upload objects that are larger than 5 GB in size.

## Usage

```
python s3upload.py ckanholding databag.ext
```

## Requirements

Tested on Mac OSX with Python 2.7.12 and Python 2.7.11

## Installation

Copy s3upload.py to your local machine. Add the previously provided AWS access key to the the following location:

```
AWS_ACCESS_KEY_ID = ' '
AWS_SECRET_ACCESS_KEY = ' '
```

## Troubleshooting

```
Traceback (most recent call last):
  File "s3upload.py", line 4, in <module>
    import boto
ImportError: No module named boto
```
Try running:
```
sudo pip install boto
```


## Contributors

Thanks to http://codeinpython.blogspot.com/2015/08/s3-upload-large-files-to-amazon-using.html



