# Market-and-News-API

## **Financial Data (Stocks, Cryptocurrencies & News)**

## **Collaborators:-**
- **Sameer Gupta (2021093)**
- **Divyajeet Singh (2021529)**
- **Medha Hira (2021265)**

## **APIs used:-**
- [POLYGON.io](https://polygon.io/stocks?gclid=CjwKCAiA1JGRBhBSEiwAxXblwWhTcFQp0pd5IPGt67Gcro-uh_QVw4CQOyfM3V5ys0cY5umc3cT4ARoC0kUQAvD_BwE)
- [ALPHA VANTAGE](https://www.alphavantage.co/)

--------------------------

## **Project Description**
The text based project operates in the finance domain, one of the most popular and sort out sectors. 

### **Stock News**

It would allow you not only to gather **Stock News** of companies you choose, but also news that have any references of that company present.  For each news displayed you are given the option to directly go to the news article link, or skip to a different news.

    Steps:
    1. Run the program
    2. Enter "News" / "NEWS" / "news".
    3. Choose a company name, for example "Apple"/"apple" for news related to Apple.
    4. Enter the number of headlines you would like to see, for example "2" for 2 headlines related to or referring to the chosen company. Press "Enter".
    5. You are given a date to choose, the news is displayed according to what news you choose. The format for the same is "YYYY-MM-DD", for example "2020-04-05" for 5th April 2020.
    6. For each news displayed, you have the option to either type "Yes" and thus will be directed the news article online, or choose "No" to go ahead onto the next news.

### **Stock Data**
This option allows you to get data such as "opening prices", "closing prices", "highest price", "lowest price" and "Max traded volume" for the stock you chose and for the duration you chose. It displays the information in a beautiful chart format which is more visually appealing.

    Steps:
    1. Run the Program.
    2. Enter "Data"/"data"/"DATA".
    3. Enter a company name, for example "Apple/apple" for stock data related to apple.
    4. Enter the time interval or period you want to see the data for, 
        Minute: Provides data for minutes as fetched by the API.
        Hour: Provides data for hours as fetched by the API.
        Day: Provides data for days as fetched by the API.
    5. Enter the "From" date, i.e. the date you want the see the data from. The entered format should be "YYYY-MM-DD", example "2020-04-05".
    6. Enter the "To" date, i.e. the date you want to see the data to. The entered format should be "YYYY-MM-DD", example "2020-04-07".
    7. Enter the currency in which the data should be displayed, for example "INR" / "INDIAN RUPEE" for Indian currency.
    8. The chart that pops up displays the following information in a chart format. 

### **Cryptocurrency Data**
   This option allows you to get data such as "Highest value", "Lowest Price", "Opening value", "Closing value", "Max Traded Volume", "Max Market Cap", all the data is displayed in the currency that you choose, basically converting everything from USD using the latest price rate. 
   Everything is displayed in another chart display. 

    1. Run the Program.
    2. Enter "Crypto"/ "crypto".
    3. Enter the digital currency you would like to see, for example "BTC"/ "Bitcoin" for Bitcoin.
    4. Enter the currency in which you would like to view the data in, for example "INR" / "Indian rupee" for indian Rupee.
    5. Enter the time interval for which you would like to see the data.
        Intraday: This option displays data for 1/5/15/30/60 minute intervals within the day.
        Daily: This option displays the latest data for the whole day.
        Weekly: This option displays the latest weekly data.
        Monthly: This option displays the latest monthly data.
    6. A chart pops up which displays the output in a visually appealing pattern.

----

## **External Python Module(s) Used:**- 
- **matplotlib.pyplot**:
    While running the application, if the 'ModuleNotFoundError' is raised, 
    please consider the following steps: 

      1. Open a terminal window on your computer. 
      2. type "pip install matplotlib" and hit Enter. 
      3. Wait for the installation. 
      4. After successful installation, run the application again. 



## **Examples:**
A simple walk-through using an example.
### **Stock News**

    ================================================================================

    Type 'NEWS' to get News About Stocks
    Type 'DATA' to get Latest Stock Data
    Type 'CRYPTO' to get latest crypto currency data
    Type 'EXIT' to exit the application

    Enter your choice: News

    ================================================================================

    Enter US company name: apple
    Enter the number of headlines you want: 2
    Enter date (YYYY-MM-DD): 2020-04-05

    Mentions of APPLE in Stock News on 2020-04-05:

    1.
    Title: Jon Stewart lavished praise on the social-media investment movement that drove up prices in meme stocks like GameStop
    Article URL: https://www.marketwatch.com/story/they-crowdsourced-a-way-of-rooting-out-corruption-jon-stewart-praises-reddit-apes-in-interview-with-secs-gensler-11646322596

    Interested? Open this article on the internet! Enter 'SKIP' if you do not want to open any links.
    Enter 'YES' to open the news on the internet and 'NO' to skip: no

    2.
    Title: A majority of Apple investors on Friday voted for a civil-rights audit to examine the impact of the tech giant's policies and practices on the civil rights of employees, customers and society. 
    Article URL: https://www.marketwatch.com/story/apple-investors-tell-tech-giant-to-perform-a-civil-rights-audit-11646421984

    Interested? Open this article on the internet! Enter 'SKIP' if you do not want to open any links.
    Enter 'YES' to open the news on the internet and 'NO' to skip: skip

## **Stock Data**

    ================================================================================

    Type 'NEWS' to get News About Stocks
    Type 'DATA' to get Latest Stock Data
    Type 'CRYPTO' to get latest crypto currency data
    Type 'EXIT' to exit the application

    Enter your choice: data

    ================================================================================

    Enter US company name: apple
    Enter the time interval (Minute, Hour or Day): day
    Enter 'FROM' date (YYYY-MM-DD): 2020-04-05
    Enter 'TO' date (YYYY-MM-DD): 2020-04-07
    Enter what currency you want the data in (ex: 'Indian Rupee' / 'INR'): INR

    Stock Bar Data for APPLE in INR:

    Highest price: 21895.963375
    Lowest Price: 20097.222475000002
    Opening Price: 20219.717375
    Closing Price: 21152.129212500004
    Max traded Volume: 65401743328.020004

## **Cryptocurrency Data**
    ================================================================================

    Type 'NEWS' to get News About Stocks
    Type 'DATA' to get Latest Stock Data
    Type 'CRYPTO' to get latest crypto currency data
    Type 'EXIT' to exit the application

    Enter your choice: crypto

    ================================================================================

    Enter required Crypto Currency Name/Code (ex: 'Bitcoin' / 'BTC'): BTC
    Enter what currency you want the data in (ex: 'United States Dollar' / 'USD'): INR
    Enter frequency (Intraday, Daily, Weekly or Monthly): daily

    Crypto Currency Data for BTC in INR:

    Highest Value at Market Price: 5268840.0
    Lowest Value at Market Price: 288803.4468
    Opening Value at Market Price: 3008428.9892
    Closing value at Market Price: 602090.964
    Max traded Volume: 402201.673764
    Max Market Cap: 402201.673764

## **Exiting the Application**
    ================================================================================

    Type 'NEWS' to get News About Stocks
    Type 'DATA' to get Latest Stock Data
    Type 'CRYPTO' to get latest crypto currency data
    Type 'EXIT' to exit the application

    Enter your choice: exit

    ================================================================================

    EXITING...


## **References**
- POLYGON: https://youtu.be/RLtEiDNKfkU
- ALPHA VANTAGE: https://youtu.be/PytQROAncxg
