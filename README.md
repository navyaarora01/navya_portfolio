# Navya Arora — Portfolio

A personal portfolio for Navya Arora, a software development engineer at Ericsson Enterprise Wireless Solutions.

Built with React, JavaScript, CSS, Vite, and Lucide icons.

## Features

- Responsive layout with a profile photo and custom NA logo
- Engineering highlights with expandable details
- Professional experience, technical skills, education, and open-source contribution
- NetPulse AI project feature
- Articles and publications with direct reading links
- Resume download and LinkedIn, email, and GitHub links
- Keyboard navigation and reduced-motion support

## Run locally

Requires Node.js 22.12 or newer.

```sh
npm ci
npm run dev
```

Open the local URL printed in the terminal.

## Production build

```sh
npm run build
```

The production website is generated in `dist/`. Serve it from the root of a domain. All profile, resume, and icon assets are bundled locally. Google Fonts is optional; local fallback fonts are provided.

## Edit the portfolio

| File | Purpose |
| --- | --- |
| `src/main.jsx` | Content, links, and interactions |
| `src/style.css` | Layout, typography, and responsive styles |
| `public/navya-profile.jpeg` | Profile photo |
| `public/Navya_Arora.pdf` | Downloadable resume |
| `public/favicon.svg` | NA logo and browser icon |
| `index.html` | Page title and metadata |

The contact section uses email links and does not need a backend. The YAML and telemetry graphics are illustrative. Project statistics are based on the supplied resume.

## Deployment

Deploy the contents of `dist/` to a static host at the domain root. The local `.openai/hosting.json` identifies the registered private Site and is ignored by Git.

## Repository contents

Commit `src/`, `public/`, `index.html`, `vite.config.js`, `package.json`, `package-lock.json`, `.gitignore`, and this README. Dependencies, build output, local settings, logs, and environment files are ignored. No backend environment variables are required.
