# s2-cells

hb220: I modified this script to make the following changes:

1. Three levels of S2-cells.
2. Default levels: L14 (gyms), L17 (pokestops), L19 (ingress portals).
3. Other colors by default.
4. Independent cell display depending on zoom.
5. Changed the order of drawing cells, perhaps with the white color of the internal cell it will be worse, but clearly better with the current default colors.

This plugin will allow you to visualize [s2 cells](https://pokemongohub.net/post/article/comprehensive-guide-s2-cells-pokemon-go/) on top of [IITC](iitc.me).  You can set two different configurable levels, one which is shown
on the map in a light color (should be higher cell number), and one which is marked in a darker color (should be lower). 

It's ok to set them both to the same.

If you set either of the numbers too high for your current zoom level (so it would cause your browser to freak out for drawing too many squares), we will try and determine this and not display either of them.

This is just an initial attempt and could still use a lot of work, though I consider it functional and useful enough at this time.  It's probably not going to crash/freeze your browser/tab, unless you have a huge screen.

You can learn more about [Cell Levels](https://github.com/nikolawannabe/s2-cells/blob/master/cell-guidelines.md) if you want.

This info is based largely on info from Reddit's [TheSilphRoad](https://www.reddit.com/r/TheSilphRoad), [OpenStreetMaps](openstreetmap.org), [overpass turbo](http://overpass-turbo.eu/), and simply testing by creating new portals to find out what happens.

With thanks and credit to all who have come before, including original l17 plugin submitter [vibrunazo](https://github.com/vibrunazo) and quality PR by [Dragonsangel](https://github.com/Dragonsangel).

![Configuration](https://github.com/nikolawannabe/s2-cells/blob/master/config.png?raw=true)

![Visualization](https://github.com/nikolawannabe/s2-cells/blob/master/s2-cells.png?raw=true)

[Install Current Version to IITC](https://github.com/nikolawannabe/s2-cells/raw/master/s2-cells.user.js)
