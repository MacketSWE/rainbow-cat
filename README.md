# Rainbow Cat

A small three.js game made together with a young game designer, one level per idea.

1. **Rainbows**: a rainbow-colored cat walks through the meadow looking for seven rainbows.
2. **Balloons**: the cat turns pink and blue and pops balloons.
3. **Lamps**: a red and gold leopard picks up lanterns at sunset. They follow it in a glowing train.
4. **Balls**: a yellow and brown dog hunts for balls. Watch out for the holes, or you have to start over.
5. **Cakes**: a unicorn in every color, with a silver and gold horn, collects birthday cakes. Don't touch the train going round on its track.

The game text is in Swedish.

## Play

It's a single `index.html` with three.js loaded from a CDN. Serve the folder and open it:

```sh
python3 -m http.server 5301
open http://localhost:5301/
```

`?bana=N` jumps straight to level N.

## Controls

- Arrow keys or WASD move the animal
- Click the grass to run there
- Space (or click the animal) jumps, with a meow, a roar, a bark or a neigh
