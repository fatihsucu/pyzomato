Pyzomato
========

This library provides a wrapper APIs of the Zomato.  It depends only on the standard libraries that are "batteries included" with a Python. For use pyzomato library you need to an `API_KEY ` . You can provide the `API_KEY`  and detailed information about API from https://developers.zomato.com/api


## Installation


#### From command line:

`pip install pyzomato`

#### From source code:

`git clone git@github.com:fatihsucu/pyzomato.git`

`cd pyzomato`

`python setup.py install`

## Basic Usage

```
from pyzomato import Pyzomato

p = Pyzomato(YOUR_API_KEY)
p.search(q="london")

p.getCategories()
```

### License
MIT licensed. Check the [`LICENSE`](https://github.com/fatihsucu/pyzomato/blob/master/LICENSE) file for full details.
