# FRED API Usage facilitator

![main workflow](https://img.shields.io/github/actions/workflow/status/haydenkuk/fred/main.yaml?logo=github)
![GitHub licence](https://img.shields.io/pypi/l/fred?logo=github)
![GitHub downloads](https://img.shields.io/github/downloads-pre/haydenkuk/fred/latest/total?logo=github)
![documentation](https://img.shields.io/readthedocs/fred?logo=readthedocs)
![PyPi download](https://img.shields.io/pypi/dm/fred?logo=pypi)
![PyPi version](https://img.shields.io/pypi/v/fred?logo=pypi)
![python version](https://img.shields.io/pypi/pyversions/fred?style=pypi)


FRED API
(https://fred.stlouisfed.org/docs/api/fred/)

Features
- All API endpoints included according to the fred docs(https://fred.stlouisfed.org/docs/api/fred/)

1. Installation
```sh
pip install fred
```
Requires Python 3.9+

2. Usage

1) Authentication: using dotenv
 - Created a file named ".env"
 - Add "FRED_APIKEY='YOURAPIKEY'" in the file
 - 