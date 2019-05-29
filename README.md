# IndiaHexes
This is a hexagonal representation of every constituency in India, coloured based on the victory margins of the 2019 Lok Sabha election results. 

Why hexagons? Some constituencies are geographically (comparatively) tiny, like Chennai South, for instance. Some are really big, like Ladakh. To normalise this, I wanted to represent each constituency as a hexagon. 

So that makes 543 hexagons in all. Pitch Interactive has an India hex map with 543 hexagons, but the problem was that not every constituency was tagged. Only the States were. So I decided I would do it the brute brute force way. With an India map outline, I positioned 543 hexagons MANUALLY, adding an id for each hexagon. Then, using D3.js, I rendered this on screen and manipulated the colours based on the 2019 results. The search box was done using an JQuery autocomplete plugin.

The base visulisation was taken from: https://pitchinteractiveinc.github.io/tilegrams/

This is at best an amateurish attempt by a data journalist. You are free to use this for any purpose, or add to this repository, clean up bugs etc.

