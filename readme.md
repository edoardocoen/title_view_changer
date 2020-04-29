# Periodic youtube title view changer
### Description
This takes a youtube id, gets its view count, then renames the youtube video to "This video has {views}". every x seconds you want. Inspired by Tom Scott.

### How to use

`pip3 install -r requirements.txt`
or equivalent

Create your youtube data api v3, get oauth creds and download them. rename your file to client_secret.json or replace client_secret in the code with your filename.

You can change the timer editing main.py, just edit the default (5.0) seconds that you find on line 50.

When you launch it, you need to follow the istruction to autorize the app and insert the video ID.

Remember that google allow only 10000 requests per day, every title change will burn 2 of them.
