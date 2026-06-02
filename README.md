# Games Overview

A landing page that lists the **Simple** puzzle game collection and the **Solitaire** card-game PWA with play links, source repos, and a short overview of each game’s rules.

**Live site:** [https://kimmania.github.io/games-overview/](https://kimmania.github.io/games-overview/) (after GitHub Pages is enabled)

## Games

| Game | Play | Repository |
|------|------|------------|
| Number Sums | [Play](https://kimmania.github.io/simple-numbersums/) | [simple-numbersums](https://github.com/kimmania/simple-numbersums) |
| Sudoku | [Play](https://kimmania.github.io/simple-sudoku/) | [simple-sudoku](https://github.com/kimmania/simple-sudoku) |
| Kakuro | [Play](https://kimmania.github.io/simple-kakuro/) | [simple-kakuro](https://github.com/kimmania/simple-kakuro) |
| Hitori | [Play](https://kimmania.github.io/simple-hitori/) | [simple-hitori](https://github.com/kimmania/simple-hitori) |
| Cryptogram | [Play](https://kimmania.github.io/simple-cryptogram/) | [simple-cryptogram](https://github.com/kimmania/simple-cryptogram) |
| Solitaire (17 games) | [Play](https://kimmania.github.io/game-solitaire/) | [game-solitaire](https://github.com/kimmania/game-solitaire) |

The Solitaire app includes Klondike, FreeCell, Spider (1/2/4 suits), Yukon, Easthaven, Pyramid, TriPeaks, Forty Thieves, Eight Off, Canfield, Scorpion, Monte Carlo, Clock, Baker's Dozen, and Beleaguered Castle. Use **Games** in the app header to switch variants.

## Local preview

Open `site/index.html` in a browser, or serve the folder:

```bash
npx --yes serve site
```

## GitHub Pages

Pushes to `main` deploy automatically via GitHub Actions.

1. In the repo, go to **Settings → Pages**
2. Under **Build and deployment**, set **Source** to **GitHub Actions**
3. Push to `main` (or run **Actions → Deploy to GitHub Pages → Run workflow** manually)
4. Live site: [https://kimmania.github.io/games-overview/](https://kimmania.github.io/games-overview/)

The workflow (`.github/workflows/deploy.yml`) publishes the static files in `site/` with `actions/deploy-pages`.

## License

MIT
