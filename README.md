# django-docs
Introduction to web app development using Python and Django.
# Quickstart
**For Ubuntu**
```bash
sudo apt-get install virtualenv
sudo apt-get install python3
sudo apt-get install python3-pip
virtualenv -p python3 .
source bin/activate
python manage.py runserver
```
## Issue
**bad magic number in 'application': b'\x03\xf3\r\n': ImportError**
## Solution
```bash
find . -name \*.pyc -delete
```
## Issue
**Django Server Error: port is already in use**
## Solution
```bash
sudo fuser -k 8000/tcp
```
