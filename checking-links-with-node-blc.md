# Checking links in html files

## Requirements:

* `https://github.com/stevenvachon/broken-link-checker` "blc" for short.
* python

## Running

1. Install blc
2. Start up serving the directory of html files using `python -m SimpleHTTPServer <port>`. Should see `Serving HTTP on 0.0.0.0 port 8080 ...` or something similar at command prompt.
3. At the cli in the same directory, run `blc --input="http://0.0.0.0:8080/"`


