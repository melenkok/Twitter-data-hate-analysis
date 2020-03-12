# Twitter-data-hate-analysis

* Jupyter notebook has a code for downloading the tweets of the user, here specified by the variable 'screen_name'

screen_name="realDonaldTrump"

* This script is useful because it manages to download more than 3000 tweets per day because of the:

except tweepy.TweepError as e:
    print(e)
    time.sleep(60)
