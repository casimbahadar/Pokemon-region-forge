# Region Forge

A procedural Pokémon region generator and playable fangame, in one HTML file.

Type a seed, and it builds a whole region: a world map with coastlines and
mountains, fifteen or so towns, twenty-odd routes, eight gyms with their own
badges, a League, a rival, a syndicate with a motive, and a regional Pokédex
drawn from the habitats the map actually produced. Then you play it — catching,
battling, gym badges, the League, and a postgame.

**[Play it here](https://casimbahadar.github.io/Pokemon-region-forge/)**

## What's in the box

- **A real region per seed.** Thirty world arrangements, sixteen route shapes —
  forks, cascades of ledges, loops around a lake, braided meadows, tree-walled
  gauntlets, riverside crossings, island chains — all of them verified walkable
  in both directions before they ship.
- **Open world.** Everything scales to the badges on your case, not to the order
  you do things in. Any gym, any route, any time.
- **Habitat-driven encounters.** Forests run Bug and Grass, caves run Rock and
  Steel, coasts run Water, snowfields run Ice. Species levels scatter more the
  further you get.
- **A story that uses what it generates.** The rival turns up at four badge
  milestones; the syndicate is somewhere specific and word gets around; their
  leader fights with the types their goal implies.
- **A League and a postgame.** Four to eight seats plus a champion, no healing
  between them. Then rematches, a Hall of Fame that spans every region you
  finish, a legendary quest, and shinies.
- **Bring your own art.** Load any tileset and map its tiles to roles by dragging
  a box around them — including multi-tile objects. Same for character sprites.
- **Offline.** One file, no build step, no dependencies. Pokémon sprites are
  fetched from PokeAPI when online; everything else is embedded.

## Running it

Open `index.html`. That's the whole thing.

## Deploying to GitHub Pages

1. Create a repository (public), e.g. `region-forge`.
2. Upload `index.html` to the root. **The name matters** — Pages only serves a
   file called exactly `index.html` at the root.
3. Upload `README.md` and `.nojekyll` alongside it.
4. Settings → Pages → Build and deployment → Source = *Deploy from a branch*,
   Branch = `main`, folder = `/ (root)` → Save.
5. Wait a minute or two, then refresh that settings page — it shows your live URL.

After that there is no deploy step. Commit a change to `index.html` and the live
site updates itself.

## Credits

- Pokémon data and sprites via [PokeAPI](https://pokeapi.co/).
- One gym badge set by
  [icycatelf](https://www.deviantart.com/icycatelf/art/Free-To-Use-Custom-Pokemon-Gym-Badges-502844888)
  (free to use, credit appreciated). The remaining badge sets are AI-generated.
- Pokémon is a trademark of Nintendo / Creatures Inc. / GAME FREAK. This is a
  non-commercial fan project and is not affiliated with or endorsed by them.
