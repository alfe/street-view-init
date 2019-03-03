# street-view-init
sample for making your custom street view.

# How to make your streetview

## Get API key
please get api key from https://developers.google.com/maps/documentation/javascript/get-api-key#quick-guide

and add key to index.html, after '&key='.  
ex: js?callback=initPano&key=abcdefgYourMapPlatformApiKeyxyzzzz 

## Arrange picture
Take 360° picture and rename to 'pano00.png'.

## Set  tileSize and worldSize
change next lines in index.html
```
tileSize: new google.maps.Size(4096, 4096),
worldSize: new google.maps.Size(4096, 2050),
```
Mostly it is good to set picture size.

Example, size of your picture is 2048 * 1024
```
tileSize: new google.maps.Size(2048, 1024),
worldSize: new google.maps.Size(2048, 1024),
```
## Open index.html with a browser
enjoy ;)

