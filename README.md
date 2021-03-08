# PaRsys
Log Parsing and Analysis Tool that converts 5G/4G logs in visual call flow diagram

## Dependecies
[Python 3.8.6](https://www.python.org/downloads/release/python-386/) to install python

## Installation on local system
Extract the received package PaRsys.7z

Navigate to installed directory and create a [virtual env](https://docs.python.org/3/library/venv.html) and activate it from cmd

Run the following command, it will automatically install all dependencies 
```python
pip -r install requirements.txt
```

## Usage
Activate virtual env if not activate

Navigate to directory with manage.py file eg.D:\PaRsys\PaRsys\manage.py and run following cmd 
```python
python manage.py runserver
```

Development server will start at [localhost](http://127.0.0.1:8000/).

In the UI select dictionary from available options and click Load Dictionary.

Select Log File as per dictionary and click Process Log, Call flow diagram will be generated.

Select Filter from options available and click Filter to reload the call flow diagram.

If another log to select click button with lock icon to select dictionary and file again.

## License
Radisys
