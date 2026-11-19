# Scheme Saathi AI

A polished, responsive, no-build browser demo for discovering Indian government schemes. Designed for a quick faculty presentation and later deployment as a static website.

## Open the app

Double-click `index.html` (or drag it into Chrome, Edge, or Firefox). No compiler, package install, server, or API key is needed for the demo.

## Included

- Dark, glass-inspired dashboard and responsive mobile layout
- Email/password demo sign-in (profile stored in this browser only)
- Search, category and state filters for a curated starter set of 25 schemes
- Scheme cards, details, official links, and local bookmarks
- Four-step eligibility discovery quiz
- Helpline directory
- Language selector for English and 12 major Indian languages
- Saathi chat demo with scheme discovery and language selector
- Links to the official myScheme catalogue for the full and changing inventory

## Scheme catalogue and freshness

The app includes a curated starter collection, not a copy of every Indian scheme. The official myScheme directory listed 5,145 schemes when this demo was prepared. Its listings and scheme rules change; use [myScheme](https://www.myscheme.gov.in/search) and the individual official scheme websites for complete, current information. Scheme entries link to official portals where identified. Helpline numbers should be verified with their official provider before use.

## Demo limitations

Sign-in and bookmarks are browser-local demo features; there is no account server or password authentication. Saathi is a scripted discovery demo, not a connected AI model. It does not require or contain an API key. The language selector demonstrates language coverage but does not yet translate every UI label or generate 22-language AI responses. Those production capabilities need a translation layer and a secure server-side LLM integration. Do not collect real credentials in this demo.

## Publish on GitHub Pages

1. Create a GitHub repository and upload `index.html`, `style.css`, `app.js`, and this README.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. GitHub Pages will provide a shareable website URL after deployment.

The site is static, so it can also be deployed to Netlify, Vercel, or any static host without a build command. A custom AI backend must be hosted separately; never place a private API key in browser JavaScript.
