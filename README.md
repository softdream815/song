## booking.com_crawler

An advanced crawler for extracting hotels data from *[Booking.com](https://www.booking.com/)*. The bot is powered by Selenium webdriver and purely written in python.
The primary intended audience is anyone interest in data mining or web scraping and would want to scrape hotel data from booking.com website. if that's you; go ahead clone this repo or fork it. For audience who are new to programming I have worked so hard to make sure that the crawler works for you. However, there are few things you need to do on your own, Your need to setting up environmental variables for the webdriver. The webdriver is like an engine that controls the crawler behaior.

## Summary
Booking.com is an online travel agency for lodging reservations & other travel products. The booking.com_crawler is an web scraping bot that crawls the booking.com website to extract hotel data. The crawler is designed to automatically generate date range and therefore the end-user is required to entered relevant data in a csv file found in a folder named. 

      client_input/destination_param.csv
## Data Features 

The bot returns the following data features saved in csv file.

      City Name 
      Hotel Name 
      location
      Hotel Price 
      Hotel Type
      Hotel Score
      checkin
      checkout
      adult
      rooms

## Getting Started

To get started using booking.com_crawler follow the following instructions.


## Installation

Two ways to intall the project. 

1. Clone repository.    

            git clone https://github.com/gilbertekalea/booking.com_crawler.git

2. Download the project files.

            Save the files on your computer. 

Once you have it installed, open code editor/terminal/command line of your choice and navigate to the folder where you saved the project files. 

## Activate Virtual Environment

To activate virtual environment run the following script in command line. Please refer here [Python Virtual Environment](https://docs.python.org/3/tutorial/venv.html) on how to activate venv in your machine.

For windows powershell : 

            my_bot\project_folder_dir> venv\Scripts\activate.ps1 

Now install the dependencies using the requirements.txt file.

            my_bot\project_folder_dir> pip -r requirements.txt

## Selenium

In order for this project to work in your computer; You need to have a selenium and python installed in your computer. 
I assume if you are interested in this project,you already know the basics of python and you have python installed. 

For window users: Open windows terminal and open project directory. 

    pip install selenium

## **Drivers**
Selenium requires a driver to interface with the chosen browser. Firefox, for example, requires geckodriver, which needs to be installed before the below examples can be run. Make sure it’s in your PATH, e. g., place it in /usr/bin or /usr/local/bin.

Read more about webdrivers here [Selenium Installation](https://pypi.org/project/selenium/) and [Selenium Official documentation](https://www.selenium.dev/documentation/webdriver/)


## **Downloading WebDriver**
This project uses chromedriver. I understand that you're using a different browser;

Here are download links for most popular browsers. 

[Chrome](https://chromedriver.chromium.org/downloads)

[Firefox](https://github.com/mozilla/geckodriver/releases)

[Edge](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/)

[Safari](https://webkit.org/blog/6900/webdriver-support-in-safari-10/)

Once you download your prefered driver; You can either save the .exe file in your project folder or you can save it somewhere in the your computer and provide the path. I recommend you save it in a different folder within the project folder or somewhere in your computer and use system path methods to access it. 

## QUICK GUIDE
### CLIENT_INPUT


