# Review Paper Prompt Builder

A tap-through decision-tree tool for generating high-quality AI prompts for academic review papers — no typing required except your topic and objective.

## What it does

Walk a 9-step decision tree (review type, citation format, output length, tables, etc.) by tapping options, then generate one of eight prompt types:

- Master prompt (full manuscript framework)
- Quick prompt
- Chapter prompt
- Citation audit
- Critical-depth revision
- Coherence edit
- Tables + figure prompt
- Submission checklist

Copy the generated prompt into Claude, ChatGPT, Jenni, or any LLM of your choice.

Runs entirely in the browser. No server, database, or API key required.

## Files

- `index.html` — the whole app, self-contained
- `.nojekyll` — prevents unwanted Jekyll processing on GitHub Pages
- `LICENSE` — MIT license

## How to use locally

Open `index.html` in any modern browser.

## Deploy on GitHub Pages

1. Go to **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and `/root` folder, then save.
4. GitHub Pages will publish the site at:

```
https://<your-username>.github.io/review-paper-prompt-builder/
```

## License

MIT License. You may reuse, adapt, and modify this project.
