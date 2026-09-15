# GameForAll — Menu

The home page for GameForAll. It asks for a player name once (stored in
`localStorage` under `gameforall.playerName`) and lists the available games as
cards that link to each game's own site.

Each game lives in its own repo and is deployed separately with GitHub Pages.
Because every repo on the same account is served from
`https://<your-username>.github.io/<repo>/`, the links here are relative
(`../UltimateTTT/`) and work without editing a username anywhere — the game
repos just need to keep the names used in the links.

## Hosting

1. Create a GitHub repo named `Menu` and push this folder.
2. Settings → Pages → deploy from the `main` branch, root folder.
3. Open `https://<your-username>.github.io/Menu/`.

## Adding a game

Copy one of the `<a class="game">` blocks in `index.html`, change the title,
blurb and `href`, and push.
