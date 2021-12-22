# gradesChecker
it's a Python script that will log in to the OdusPlus (University system) where students can see the grades of their courses and check if any new grade is uploaded in the current semester it will send an email to you :)

# Installation and setup
## install required dependencies
```
    pip install -r requirements.txt
    or
    py -m pip install -r requirments.txt
```
## Update config.py
Update your current semester XPath and put your email and odus credentials  
(For gmail you might want to put application password and allow less secure apps so that google doesn't block the code)  
How to copy your currentSemesterBodyPath:  

![Screenshot](XPath.jpg)


### run with ``` py main.py ```
#### if your chrome version is different you might need to change the chromedriver.exe
https://chromedriver.chromium.org/downloads

#### Docker is fun
If you are familiar with docker and want to run the script inside a container check this image [joyzoursky/python-chromedriver](https://hub.docker.com/r/joyzoursky/python-chromedriver/)
