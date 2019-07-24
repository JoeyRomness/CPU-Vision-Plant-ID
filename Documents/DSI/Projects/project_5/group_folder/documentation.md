# Problem Statement:

### Data Science Perspective:
- Is it possible to develop a tool that, using a set of keywords, can identify natural disasters events and, from that information, discern the geolocation of said disaster?
### Client Perspective:
- The client has asked us to provide a tool that, through the usage of a customizable list of keywords that corresponds to disasters, monitors live streams of social media posts (in this case, Twitter) and then provides the geolocation of each post.

### Deliverables We Need
- A short write-up describing the project.
- Open source code to allow for implementation of this big data search process during a disaster.
- The code should be flexible enough and allow the end user to change certain keywords which would correspond to different disaster types, e.g.: “flood”, “water”, “depth”, for a flood event and “burn”, “fire”, “smoke” for a wildfire event. Possible disaster events include floods, fires, hurricanes, earthquakes, tornadoes, tsunamis and volcanoes.
- Output of this code should be a geolocated dataset (a GIS shapefile or json with lat/long reference, or a KML file) with relevant information acquired from the tweet as attribution
- A preliminary proof of concept using a real-world example.

## Initial Process:
- Gather Data (using twitter API) 
- IMPORTANT: Develop Keyword Dictionary -- Figure out how to effectively clean data so that Keywords are actually discerning disasters and not just noise.
    - Regex, Stopwords, MAYBE Lemm/Stem
    - Potentially customizing stop words list? TBD
- FOR Keywords: Are we developing a list specific to one disaster or making a big master list that can identify disasters in general? 
- NLP/Feature Engineering
    - AKA Sentiment Analysis

### Resources:
- Massive Twitter Hurricane Sandy Dataset w/ geolocations and other data attributes
https://github.com/mdredze/twitter_sandy/blob/master/data/release.tgz (We found this dataset by referencing previous DSI-LA project work)