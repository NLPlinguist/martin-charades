# Martin Charades

A simple charades clue generator for family game night. Pick a category, hit **Next**, and start acting.

## Categories

- **All** — everything combined
- **Kids Movies** — Disney, Pixar, and popular kids' movies (past 40 years + classics)
- **History** — people, events, and inventions
- **Animals**
- **Wacky Random** — silly random combinations
- **Family** — Mom, Dad, Wade, Joyce, Mabel, Barry, Cash, Noah

## Run locally

Just open `index.html` in any browser — no build step, no dependencies.

## Publish to GitHub Pages

1. In the GitHub repo, go to **Settings → Pages**.
2. Under *Build and deployment*, choose **Deploy from branch**.
3. Select the `main` branch and the root folder (`/`).
4. Save. Your site will be live at `https://nlplinguist.github.io/martin-charades/` (usually within a minute or two).

## Adding extended family names

Open `index.html`, find the `family` array near the top of the `<script>` block, and add names:

```js
const family = ["Mom", "Dad", "Wade", "Joyce", "Mabel", "Barry", "Cash", "Noah"];
```

Then push the change to the repo — GitHub Pages will pick it up automatically.
