## shopify-bot 

** WORK IN PROGRESS **

Uses Python 3/Selenium Web Driver 

## What This Bot Can Do
Checks out a specific shoe in a specific size with a given URL.

**Currently only works for Amex cards only

## Setup
1. Install Python 3
2. Clone repo/download .zip 
3. Install the required packages in PIP:
  - <code> pip install selenium </code>
  - <code> pip install requests </code>
4. Download the appropriate [ChromeDriver](https://chromedriver.chromium.org/)
5. Change variables in main.py
6. run script
  - <code> main.py <code> or <code>python main.py</code>



## Changes Made
- Improved checkout time by using WebDriverWait instead of sleeping 
- Checks through new arrivals for products of a certain brand (given by user)
- Built URL Reader/Feeder with user Input