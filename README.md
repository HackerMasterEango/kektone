### Purpose

Easily sort through youtube video transcripts to find points of interest. This is very useful
software to expedite the process of cancelling youtubers you do not like.

## Scripts

# kektone.py

goes through steak and eggs podcast videos. update the variable `problematic_words_and_phrases`
to find the timestamps for certain words in the video transcript file. It will give you the video
id which you can enter in the browserurl to find the video.

Installing and running script

1. source venv/bin/activate
2. pip install -r requirements.txt
3. python kektone.py

# fetch-podcats.js

fetches latest podcast. Running this you need a dev youtube api key.

Installing and running script

1. npm i
2. node fetch-podcasts.js
