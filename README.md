# windy-plugin-inreach
Represent a KML feed from Garmin inReach device (MapShare) in a Windy map

# Quickstart

Generate your own API Key at https://api4.windy.com, then search & replace the `REPLACE_YOUR_API_KEY_HERE` word by the API Key in index.html :

```javascript
  const options = {
    key: 'REPLACE_YOUR_API_KEY_HERE',
    lat: 14,
    lon: -29,
    zoom: 4
  }
```

Then, you have to update manually a MapShare feed (in KML format) and rename it `example-mapshare.kml`. & Enjoy!


# Future improvement

Next version of the app will be installable in Windy directly, and you will be able to specify a MapShare feed ID directly.
Future needs will be to import another KML or GPX trace -in the future- to do weather forecasting and see the impact of the weather on the future route.

