**Selenium-WebDrive-Python-Example**	

This repository contains the base setup of an UI testing project, using Python, Selenium Webdriver and Page Object Model pattern.

Requirements
Setup & configure WebDriver in Pycharm
---------------------------------------
Pre-requisites:
----------
  Selenium 4.22.0
  
  Python 3.11
  
  Pychamp

1) Download browser specific drivers using below links....	

    Chrome:	https://chromedriver.chromium.org/downloads
    
    Edge:	https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/
    
    Firefox:	https://github.com/mozilla/geckodriver/releases	
    
    Once you donwloaded, extract .zip files then you will see .exe files ( they are drivers)

2) setup selenium webdriver
   
	Appraoch#

    pip install selenium
   
	Appraoch#2:

		or through Pycharm project settings...

**Test Execution**

    Open a terminal

    py.test .\test_ContactForm.py -s

    py.test --alluredir C:\SeleniumPython\SeleniumFramework\reports\allureReports test_ContactForm.py

    # generate allurereport to HTML file
    allure serve C:\SeleniumPython\SeleniumFramework\reports\allureReports
    
    py.test --alluredir C:\SeleniumPython\SeleniumFramework\reports\allureReports test_suit.py
