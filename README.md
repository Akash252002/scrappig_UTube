
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
![ytHome]![Screenshot 2023-03-20 214840](https://user-images.githubusercontent.com/97967936/226414482-813d27bd-c090-4cf6-a5b6-eb89907a34b9.png)

- Results :
![yt_res1]![Screenshot (22)](https://user-images.githubusercontent.com/97967936/226414518-ede155dd-3e41-4f4d-8ba4-10ba746c539d.png)

- Database :
![yt_db]![Screenshot (23)](https://user-images.githubusercontent.com/97967936/226417381-9b2d57e6-6110-4e93-af1b-ac99b240e184.png)


- according to ques:

- url: https://www.youtube.com/@PW-Foundation/videos
- input channel name: PW-Foundation
![PW-Foundation]
![pwss2]

data is saved in the csv file: https://github.com/Akash252002/scrappig_UTube/blob/main/videos_data.csv
