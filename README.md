# leaflet-map-polygon-tabs
Leaflet thematic polygon map, with hover info, tabs to display time periods, and data drawn from GeoJSON file

## Demo
http://jackdougherty.github.io/leaflet-map-polygon-tabs

## Credits
- Map design by Connecticut Mirror http://ctmirror.org

## Limitations
- legend displays only numerical ranges, not text values

## Create your own
- see Leaflet templates section of *Data Visualization for All* book http://datavizforall.org

## Compare with
- http://github.com/jackdougherty/leaflet-map-polygon-tabs-js

## To Do
- Add "keydown" code to allow users to press the "tab" key to flip through tabs, to give the appearance of animation over time. Also this will help visually impaired users. Alvin Chang recommends: It would require an event called "keydown" -- and from there, you would have to be able to keep track of what year is currently clicked... and then a "right arrow" push would push a year 10 years ahead of that, and vice versa. See these answers: http://stackoverflow.com/questions/4104158/jquery-keypress-left-right-navigation and http://stackoverflow.com/questions/19347269/jquery-keypress-arrow-keys
- Make code responsive for smaller devices. Hover does not work in iOS or Android tablets. Alvin Chang recommends: Maybe for smaller devices, instead of the menu bar at the top, you could have a pulldown menu? Also, right now there's a click and a hover event -- the click for mobile. One thing you could look into is jQuery Mobile, because that will give you a "tap" event, which makes it work better on mobile.
