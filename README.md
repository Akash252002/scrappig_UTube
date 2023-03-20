
# lab-flask

<!-- ![image](https://user-images.githubusercontent.com/115451707/196919992-edcfea8b-e3f6-4f35-9398-43be66b5622d.png) -->
- The url or channel name can be hard coded but not done to make it more flexible and available
- To fix channel name , go to application.py file and replace the channel_name with the given name:
Like for example in the url:  "https://www.youtube.com/@PW-Foundation/videos" , replace channel name with "PW-Foundation"
- Enter the name of channel whose latest 5 videos content (video url, video id, datetime of scraping, date of video posted, views count, video thumbnail url) you want to scrape.
- libraries used are mentioned in the requirements.txt
- The website is hosted on Microsoft Azure 
(The link is temporarily down/not working....will fix it soon)
- Link : ```scrutube2.azurewebsites.net ```

```
You Tube Videos Scraper using Flask (Python) : ScrapeTube 1.0
```
To run flask application :
1. Install the requirements.txt file for the python libraries:
```
pip install -r requirements.txt
```
2. Run the app:
```
python application.py
```

To access your flask application open new tab in and paste the url:
```
https://{your_url}.pwskills.app:5000/
```
- Home Page: Search Channel Name
![ytHome]
- Results :
![yt_res1]
- Database :
![yt_db]

- according to ques:

- url: https://www.youtube.com/@PW-Foundation/videos
- input channel name: PW-Foundation
![PW-Foundation]
![pwss2]

data is saved in the csv file: 
