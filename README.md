# Arrays Docs

Source for [docs.arrays.org](https://docs.arrays.org), built with [Mintlify](https://mintlify.com).

## Local development

```bash
# install Mintlify CLI
npm i -g mintlify

# preview locally on http://localhost:3000
mintlify dev
```

## Structure

```
arrays-docs/
├── docs.json                # Site config (navigation, theme, logo)
├── welcome.mdx              # Home page
├── quickstart.mdx           # 5-step getting started
├── concepts.mdx             # Glossary of key terms
├── skills/                  # AI Agent Hub
│   ├── overview.mdx
│   ├── install-claude-code.mdx
│   ├── install-cursor.mdx
│   ├── install-codex.mdx
│   └── prompts.mdx
├── nanopayment/             # Pay-per-call (x402 + Circle Gateway)
│   ├── overview.mdx
│   └── quickstart.mdx
├── api-reference/           # REST API docs
│   ├── introduction.mdx
│   ├── authentication.mdx
│   └── errors.mdx
├── pricing.mdx
├── support.mdx
├── logo/
│   ├── light.png
│   └── dark.png
└── images/
    └── og.png
```

## Deploy to Mintlify

1. Push this repo to GitHub
2. Go to [mintlify.com/dashboard](https://mintlify.com/dashboard) → New Project
3. Connect this GitHub repo
4. Mintlify builds and serves a preview URL automatically
5. (Optional) Add a CNAME `docs.arrays.org` pointing to Mintlify

Every push to `main` triggers a re-deploy.

## To-do for v1 launch

- [ ] Replace placeholder pricing copy with final numbers
- [ ] Import full OpenAPI spec from `data-tools.prd.space.id/swagger` into `api-reference/`
- [ ] Add 3–5 Cookbook recipes
- [ ] Set up `docs.arrays.org` CNAME
- [ ] Set up 301 redirect from old `/swagger/index.html` to new docs

## License

Copyright © 2026 Arrays Data. All rights reserved.
