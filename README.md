# Jinpa — Web Platform

Source code for [getjinpa.com](https://getjinpa.com) — the free website platform for Tibetan monasteries, dharma centers, artists, teachers, and writers.

## What this repo is

This is the **Jinpa marketing site and setup wizard**. It is not a template. If you are looking to create your own site, go to [getjinpa.com/templates](https://getjinpa.com/templates).

## License

**This repository is licensed under the Business Source License 1.1 (BUSL-1.1).**

You are free to:
- Read, study, and learn from this code
- Run it locally for personal or development use
- Contribute to the project

You are **not** permitted to:
- Use this code to offer a competing hosted service
- Build a commercial product derived from this code
- Deploy this code for commercial purposes

without explicit written permission from the Jinpa Project.

**On March 4, 2030**, this license automatically converts to the MIT License, at which point full open source rights apply.

For commercial licensing inquiries: hello@getjinpa.com

See [LICENSE](./LICENSE) for the full license text.

## Templates

All Jinpa **templates** (inkwell, common-ground, lantern, stone-gate, vermillion, dhc-stillwater, starter-blog) are separately licensed under the **MIT License** and are free to use, modify, and distribute without restriction.

## Running locally

```bash
npm install
npm run dev
```

## Stack

- [Astro](https://astro.build) — static site framework
- Deployed to GitHub Pages via GitHub Actions
- OAuth handled by a separate Cloudflare Worker ([getjinpa/auth](https://github.com/getjinpa/auth))
