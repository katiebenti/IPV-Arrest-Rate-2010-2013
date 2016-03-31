# leaflet-map-polygon-tabs
Leaflet thematic polygon map, with hover info, tabs to display time periods, and data drawn from GeoJSON file

## Demo
http://jackdougherty.github.io/leaflet-map-polygon-tabs

## Credits
- Map design by [@alvinschang](https://github.com/alvinschang) Connecticut Mirror http://ctmirror.org
- Code improvements by [@ilyankou](https://github.com/ilyankou)

## Pros
- Uses tabs to display data series for one map boundary over time (such as years or categories)
- Use arrow keys to flip through tabs, for example, to animate change over time
- Hover over polygon to view info
- Easily create and upload data by joining a CSV table to a GeoJSON map boundary

## Cons
- User needs to manually set the cut-off ranges in the script.js file, which auto-creates legend
- Automated legend displays only numerical ranges, not text values
- Not yet designed for mobile devices; look at jQuery Mobile on to-do list

## Create your own
- see Leaflet templates section of *Data Visualization for All* book http://datavizforall.org

## Compare with
- http://github.com/jackdougherty/leaflet-map-polygon-tabs-js

## To Do
- Decide where to insert hint to use arrow keys to advance through tabs
- Make code responsive for smaller devices. Hover does not work in iOS or Android tablets. Alvin Chang recommends: Maybe for smaller devices, instead of the menu bar at the top, you could have a pulldown menu? Also, right now there's a click and a hover event -- the click for mobile. One thing you could look into is jQuery Mobile, because that will give you a "tap" event, which makes it work better on mobile.
