# Portfolio
# Daryl Benson | Portfolio

Personal portfolio for Daryl Benson, talent acquisition lead who builds hiring systems for fast-growing tech companies, and builds recruiting tools with AI.

**Live site:** https://your-site-name.netlify.app <!-- TODO: replace with your Netlify URL or custom domain -->

## What's on the site

- **Builds:** recruiting tools built with AI coding assistants, including a compensation benchmark tool (V1) and an AI recruiter and outreach Chrome extension (V2)
- **Talks and podcasts:** conversations on talent acquisition, AI and breaking into cyber
- **Contact:** a contact form handled by Netlify Forms

## Tech stack

| Stage | Stack |
| --- | --- |
| Now | Static HTML and CSS, deployed on Netlify |
| Next | Astro, Netlify Functions, Claude API |

## Run it locally

Right now the site is a single static file, so you can open `index.html` in a browser.

For a local server that behaves more like production:

```bash
npx serve .
```

Once the project moves to Astro, this section becomes:

```bash
npm install
npm run dev      # local dev server at http://localhost:4321
npm run build    # production build into dist/
```

## Deployment

The site deploys automatically to Netlify on every push to `main`.

| Setting | Static (now) | Astro (later) |
| --- | --- | --- |
| Build command | none | `npm run build` |
| Publish directory | `.` | `dist` |

Secrets such as API keys go in Netlify under **Site configuration > Environment variables**, never in this repo.

## Project structure

```
.
├── index.html     # the whole site (for now)
├── README.md
├── LICENSE
└── .gitignore
```

## Roadmap

- [ ] Migrate to Astro with components and a data file for builds and talks
- [ ] Case study page for each build
- [ ] Live AI outreach demo powered by a Netlify Function
- [ ] Bring the compensation benchmark tool under the same domain
- [ ] Writing section for posts on hiring and AI

## License

The source code is released under the [MIT License](LICENSE). Personal content, including my photo, CV, written copy and media, is not covered by the license and remains © Daryl Benson, all rights reserved.
