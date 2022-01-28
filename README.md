# Automate Stocks and Crypto Research with Python and Deep Learning

Built a Python Pipeline that **Scrapes, Summarizes and Calculate Sentiment Score** from Stock and Crypto News Articles from web.


1. The Scraping of the News Articles is done using BeautifulSoup-Python.
2. The deep learning model is developed using ***Hugging Face Transformer- Pegasus Financial Model.***
3. The Sentiment Analysis is then done on the Summaries, and a sentiment score is generated via Transformers Pipeline classified as POSITIVE OR NEGATIVE.
4. The Final Output Csv is present in the repository.

The Scraping of News Articles is done from [Yahoo Finance.](https://finance.yahoo.com/)



## How to run this pipeline?

1. Clone or download this repository to your local machine.
2. Install the required libraries mentioned in the project.
3. Run the ``app.py`` command on your command prompt.
4. Pass the Code of the Stock/Crypto you want the analysis about in the `````monitored_tickers````` , for example: TSLA for Tesla, INFY for Infosys, etc.
5. Run the command, and the pipeline will automatically generate a CSV file containing all the details.

## Usage
 
<p align="center">
  <img width="300" height="200" src="https://github.com/parthkohli92/Stocks-and-Crypto-Analysis/blob/main/images/Capture.PNG">
</p>
