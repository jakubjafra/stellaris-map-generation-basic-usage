Stellaris map generation - basic usage
======================================

Simple web serwer that gets output from [Stellaris map generation](https://github.com/khronedev/stellaris-map-generation) scripts and turns them into charts using Three.js 3d lib.

Usage
-----

```
npm i
node server.js
# GOTO: http://localhost:3690/test
```

Demo
----

From such a game state:
![Game state](https://raw.githubusercontent.com/khronedev/stellaris-map-generation-basic-usage/master/samples/test/showcase/game_screen_shot.png)

Generated charts:
![Generated charts](https://raw.githubusercontent.com/khronedev/stellaris-map-generation-basic-usage/master/samples/test/showcase/generated_regions.png)

Take special look at different regions that are highlighted:
1) Top left corner - independent beings in galaxy (alliances and independent empires)
2) Top right corner - sectors
3) Bottom left corner - empires
4) Bottom right corner - individual solar systems colored by number of pops living there

Those are pretty basic maps that show **different levels of details** and **basic demographic overview** that you can achive using those tools. You can analyse your game from "ground" level of solar systems all the way up to independent empires and alliances.
