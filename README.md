Berlin SVG Viewer
=================

This viewer is used to view games on [Berlin](http://www.berlin-ai.com).

How to use
----------

This repository includes a test `index.html` that loads a local **map** and **game** in `.\data`.

So to view a game with this viewer, you must have those files hosted on your server.

To obtain those files, you can send a `GET request` at:

* map: `http://berlin-ai.com/maps/id.json` where `id` is the id of the map.
* game: `http://berlin-ai.com/games/id.json` where `id` is the id of the game.
