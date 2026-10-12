# Gravity Menagerie Mobile

A touch-friendly HTML5 version of [Gravity Menagerie](https://github.com/kurosatto/Gravity-Menagerie),
the Processing game by Rebecca Taylor and Kursat Mestav. Steer a black hole to pull your farm animals
toward their food without letting them hit the spikes, fall into the hole or get eaten by the wolf.

## Play

Open `index.html` in any phone or desktop browser. For a link you can open on your phone, turn on
GitHub Pages for this repo (Settings > Pages > Deploy from branch `main`, folder `/`).

Drag anywhere on the screen to move the black hole. The rules follow the original sketch: the run timer
moves you from Level 1 to Level 2 at 20 seconds and to Level 3 at 40 seconds, the game ends at 60 seconds,
and your score is the seconds you survived. Any animal that touches a wall, falls into the black hole or
gets caught by the wolf ends the game (so does the black hole hitting a wall or the wolf). Space Mode is a
sandbox where nothing dies and you can add animals and black holes.

No build step or dependencies: one HTML file plus the images in `img/`.
