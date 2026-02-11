# Research Radar

A live research paper feed for materials science researchers. Pulls real papers from [OpenAlex](https://openalex.org) — an open catalog of the world's scholarly works. No API key needed.

## Topics

- High-Entropy Alloys
- Electrocatalysis
- ML for Materials
- AI in Science
- Engineering Physics
- Trending in MatSci

## How it works

1. Click a topic pill — papers load instantly from OpenAlex
2. Sort by Most Recent, Most Cited, or Most Relevant
3. Results show title, authors, journal, abstract, citation count, and open-access links
4. 10-minute client-side cache per topic/sort combo

## Deploy

The site is a single `index.html` with no build step. To enable GitHub Pages:

1. Go to **Settings > Pages** in your repo
2. Under **Source**, select **Deploy from a branch**
3. Pick `main` branch, `/ (root)` folder, and save

The site will be live at `https://<username>.github.io/pocto-garbanzo/`.
