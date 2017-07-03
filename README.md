# Twitter Scrape

Scrape tweets from twitter into a DB.  Convert the DB to a CSV file.

## Setup

* Create an application [here](https://apps.twitter.com/).
* Set the following keys in `settings.py`.  You can get these values from the app you created:
    * `CONSUMER_KEY`
    * `CONSUMER_SECRET`
    * `ACCESS_TOKEN`
    * `ACCESS_SECRET`

## Usage

* `python scrape.py` to scrape.  Use `Ctrl + C` to stop.
* `python dump.py` to generate `tweets.csv`, which contains all the tweet data that was scraped.
* If you want to edit behavior, change settings in `settings.py`.