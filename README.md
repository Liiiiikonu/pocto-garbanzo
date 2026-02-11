# Research Radar

A live research paper feed for materials science researchers. Uses the Anthropic API with web search to pull the latest papers, breakthroughs, and articles across specific research topics.

## Topics

- High-Entropy Alloys
- Electrocatalysis
- ML for Materials
- AI in Science
- Engineering Physics
- Trending in MatSci

## How it works

1. Enter your Anthropic API key (stored only in `sessionStorage`, sent only to `api.anthropic.com`)
2. Click a topic pill to fetch live results
3. Results are cached for 5 minutes per topic

## Deploy

The site is a single `index.html` with no build step. To enable GitHub Pages:

1. Go to **Settings > Pages** in your repo
2. Under **Source**, select **Deploy from a branch**
3. Pick `main` branch, `/ (root)` folder, and save

The site will be live at `https://<username>.github.io/pocto-garbanzo/`.
