leaflet-choropleth-example
==========================

Playing with the leaflet choropleth example at http://leafletjs.com/examples/choropleth-example.html to be more customizable, smart, and handle mapping multiple attributes

To deploy:
Have python installed
go to /site/food_zones and run
`python parse_data.py`

While that churns, copy /site/local-vars.js.template to /site/local-vars.js 
If you have rights to use Rotis fonts, put your Rotis user id in that file.

copy /site/choropleth-local.css.template to /site/choropleth-local.css
If you have rights to use Rotis fonts, update this with your information.

Open the html file /site/chorpleth-example.html in a browser and everything should "just work"*.

*NOTE: Sadly, Google Chrome does not "just work" - for security it blocks calls with 'null' origins requesting local files. You can put this on a server find a workaround to this online that you read, or just use another browser.