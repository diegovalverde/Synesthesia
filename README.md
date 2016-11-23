# Synesthesia

Transform photo albums to cool music

### How it works (under construction)

1) Use Gaussian mixture models and expected maximization to segment the image into k color regions.

2) Use the colors to select music temperature according to the tones in the chromatic scale (https://en.wikipedia.org/wiki/Circle_of_fifths)

3) Use the k clusters from GMM to figure out curves/straigh lines relationships to come up with the melody.


** WORK IN PROGRESS **

### Requirements

`sudo apt-get install python-sklearn `

