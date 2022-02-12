# Guideline how to setup Robot Framework
## Getting Started

Automation Tool that was used is [Robot Framework](https://robotframework.org/).
 
### Prerequisites

In order to run the Automation script, You are required to have the following: 

1- Python `Use Default installation setting.`

2- Robot framework 3.0.4 

3- Robot framework seleniumlibrary 3.2.0

4- Chrome driver

For editing the scirpt, I Recommend to use [Pycharm IDE](https://download.jetbrains.com/python/pycharm-community-2018.1.6.exe).

### Installing

#### 1. Python

Please you need to download base on the opreting system that you are using. I recommend to Python 3.7 on the following links:

[Python for Windows](https://www.python.org/ftp/python/3.7.0/python-3.7.0-amd64.exe)

`Important` 
* for Windows users, please make sure that you click on the Add python to system variable path checkbox.
* Use default installation setting.



##

#### 2. Robot framework Libraries

##### Windows Users
* Launch Command Prompt (CMD)
* Install RobotFramework from pip



By typing the following at CMD.

```
pip install robotframework==3.0.4
```
```
pip install robotframework-seleniumlibrary==3.2.0
```
```
pip install PyYAML
```

##
#### 3. PyCharm IDE

1- You need need to download [Pycharm](https://download.jetbrains.com/python/pycharm-community-2018.1.6.exe) and use default installation setting.

2- Adding Pycharm plugins:
* Launch Pycharm
* Click on File
* Click on Settings
* Click on Plugins
* Click on Browse Repositories
* Search from Robot Framework Support
* Click on install
* Search from IntelliBot @SeleniumLibrary Patched
* Click on install
* Click on Restart-pycharm
##
#### 4. Chrome Driver

1- Please check your chrome browser version.

2- Navigate to [Chrome driver](https://chromedriver.chromium.org/)

3- Download  of a same version chrome browser that you are using.

4- Extract the file and then copy it.

5- Go python execution path if use the defult, the path will as the following:

`Replace it with your account name`

    C:\Users\{YourAccountName}\AppData\Local\Programs\Python\Python37
 
## Running the tests

To run robot test cases:
first you need navigate to Project folder.

Let say you downloaded the XProject folder to Desktop. At command prompt.
```
C:\Users\{YourAccountName}\Desktop>cd XProject
```
And then to run the script you have to execute the Test Cases as the following and prss enter
```
C:\Users\{YourAccountName}\Desktop\XProject>pybot -d Results Tests/TestSuite.robot
```
## Authors

 [**Saleh Almelinan**](https://www.linkedin.com/in/saleh-almelihan-9244315a/)
 

