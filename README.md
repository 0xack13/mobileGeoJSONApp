mobileGeoJSONApp
================

GeoJSON web mobile app with Mongodb

Import zip.json to your mongodb instance:
```
mongoimport -d geospatial -c zips data/zips.json
```

View imported data:
```
use geospatial;
2db.zips.find();
```
