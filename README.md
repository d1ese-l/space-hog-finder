# Space Hog Finder

Scan a folder and find the large, old files nobody has touched in a while — entirely in your browser. Nothing is uploaded anywhere.

## Features

- Pick any folder on your computer via the browser's native folder picker
- Filter by minimum file size and minimum time since last modified
- Automatically groups numbered/sequential files (`file0001.jpg`, `file0002.jpg`...) into a single collapsible row
- Exclude specific folders (e.g. `node_modules`) from results, either by typing a name or clicking "Exclude" on any row
- Sortable results table, a top-20 bar chart, and CSV export
- 100% client-side — no server, no accounts, no data ever leaves the page

## Usage

Just open `index.html` in a modern browser (Chrome, Edge, or another Chromium-based browser — folder selection needs `webkitdirectory` support). No build step, no dependencies, no install.

## Contributing

Issues and pull requests welcome. It's a single self-contained HTML file (`space-hog-finder.html`), so most changes are easy to review.

## License

MIT — see [LICENSE](LICENSE).
