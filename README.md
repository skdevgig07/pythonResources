# Python Resources
Below is also a list of a few resources I've used in the past for Python, along with demos I've created over the years.

## Online Demos
- Pandas Demo: https://bitly.com/MqPandas
- Web Scraping: https://bit.ly/MqWeb
- NLP Demo: https://bitly.com/MqNLP
- Image processing (OCR): http://bit.ly/MqOCR
- Yahoo Finance Demo: https://marqueegroup.ca/resource/how-to-use-python-in-a-finance-environment/

## Popular Python Packages
A couple articles I wrote on top 25 packages I use on day to day basis in Python:
- Part 1: https://marqueegroup.ca/resource/python-packages-101-part-1/
- Part 2: https://marqueegroup.ca/resource/python-packages-101-part-2/
- Cheat Sheet: https://marqueegroup.ca/wp-content/uploads/2021/03/Python-Packages-Cheat-Sheet.pdf

This link also has a great list of all the popular "finance" packages in Python:
https://github.com/wilsonfreitas/awesome-quant

## My Medium Account
https://bogdan-tudose.medium.com/
- I wrote several articles on Python Packages, using Streamlit to create interactive dashboards, and using the Yahoo Finance API to scrape live market data
- you can also find my lists of bookmarked articles on there (I've tried to categorize them by topic)
- the codes behind the Python dashboards I created can also be found on my github: https://github.com/dbogt

## Extra resources
- https://medium.com/ - this is one of the main websites I use nowadays for quick tutorials, there are various articles on here related to Python, search for example Pandas with Python, or Web Scraping with Python, Beautiful Soup with Python, etc.
- http://towardsdatascience.com/ - a lot of their articles are also on Medium
- http://www.reddit.com/r/Python 
- https://www.reddit.com/r/learnpython
- https://stackoverflow.com/ - people usually ask specific questions and best answer gets upvoted
- https://pbpython.com/ - newsletter/blog with some practical business applications
- [Explore Python](https://kandi.openweaver.com/explore/python) - Explore a curated list of Python popular & new libraries, top authors, trending project kits, discussions, tutorials & learning resources on kandi.

## Book Recommendations
- Python for Finance
  - Author: Yves Hilpisch
  - Github: https://github.com/yhilpisch/py4fi2nd
  - Link: https://www.oreilly.com/library/view/python-for-finance/9781492024323/

- Hands-On Machine Learning with Scikit-Learn and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems
  - Author: Aurélien Géron
  - Github: https://github.com/ageron/handson-ml3
  - Link: https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/


## Alternative Data Sets
The best way to practice with Pandas is to import and manipulate different data sets. Ideally, try using excel/csv files that you already have at work and use on a day to day basis. However, if you want to experiment with "cleaner" data sets (that don't have as many issues) there are a couple websites I use below.

- Kaggle: https://www.kaggle.com/ 
  - they have thousands of different public data sets that you can download and play around with; a lot of data sets are uploaded by users of kaggle
  - they also have lots of free tutorials with Python on how manipulate their data sets, use machine learning on them, etc.

- Google Data Sets: https://datasetsearch.research.google.com/
- Canadian Government data sets: https://open.canada.ca/en/open-data
- US Government data sets: https://www.data.gov/
- IMF data sets: http://data.imf.org/
- FiveThirtyEight (Nate Silver) data sets: https://data.fivethirtyeight.com/
- NASDAQ data sets: https://data.nasdaq.com/search

## Streamlit Dashboards
Links to these can also be found on my github profile page and LinkedIn.
- :fuelpump:[Gas Stations Locator](https://bit.ly/locationsDemo): Dashboard created with Streamlit and Python to plot gas station locations of Couche-Tard and Shell Canada. Pick a gas station and km radius and the app will locate all the Couche-Tard and Shell stations within that distance. App is a demo of how Python could be used in an M&A deal to help with cost synergy analysis. [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](hhttps://dbogt-locationsdemo-app-avfon4.streamlitapp.com/) 
- :chart_with_upwards_trend:[Stock Beta Calculator](https://bitly.com/StockBetaApp): Dashboard created with Streamlit and Python to calculate a stock's beta. Pick a ticker and a stock index to run the regression and calculate the beta. [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dbogt/stockbetadashboard/main/app.py) 
- :chart_with_upwards_trend:[Options Calculator](https://bit.ly/OptionsCalculator): Dashboard created with Streamlit and Python to calculate a call/put option value with Black Scholes. App also allows to scrape options chains from Yahoo Finance for a particular ticker and visualizes strike prices vs. implied vols and bid/ask/last price of option. [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dbogt/optionscalculator/main/app.py) 
- :moneybag:[Ontario Sunshine List](https://bit.ly/ONSunshineList): Dashboard that explores 20+ years of public sector salary disclosures from Ontario (https://www.ontario.ca/page/public-sector-salary-disclosure). [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dbogt/on_sunshine/main) 
- :movie_camera::trophy:[Oscars 2022 Predictions](https://bitly.com/oscarsApp): Make predictions for the top categories and compare your answers with other people around the world. Also try out the Best Picture Emoji quiz while you're at it! [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dbogt/oscars2022/main) 
- :game_die:[Board Game Collection](https://bitly.com/BGGApp): Check out your board game collection by connecting with your BoardGameGeek account. [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dbogt/bggcollection/main/app.py) 
