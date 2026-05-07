# ollaverse

A beautiful static portfolio page showcasing the entire local AI toolkit ecosystem.

25 tools across 8 categories -- management, monitoring, benchmarking, development, fleet orchestration, search, vision, and pipelines. All running 100% locally with Ollama.

## View

```bash
open index.html
```

## Features

- **Ecosystem architecture diagram** showing tool layers from discovery to deployment
- **Interactive category filters** to browse by function
- **Tool cards** with descriptions, features, language, and category
- **Responsive design** -- works on mobile
- **Zero dependencies** -- single HTML file, no build step

## Customization

All tool data is in the `TOOLS` array in `index.html`. Add a new tool by appending an object with `name`, `description`, `features`, `language`, `category`, `icon`, and `color`.

## Deploy

Drop `index.html` anywhere -- GitHub Pages, Netlify, Vercel, or just open it locally. No server needed.
