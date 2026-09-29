# PhishRange Showcase

A one-page visual overview of **PhishRange**, a Claude Code tool that triages suspicious emails and attachments on a single Windows PC. It parses the email, detonates any attachment in two throwaway VirtualBox sandboxes (one isolated, one with monitored egress), runs six analysis agents in parallel, and writes a plain-English verdict with recommended actions.

This repo contains only the showcase page (`index.html`). The PhishRange source code will be published separately.

## Viewing the page

- **Locally:** download `index.html` and open it in a browser.
- **Online:** enable GitHub Pages (Settings → Pages → deploy from the `main` branch, root folder).

The page includes an animated case walkthrough, architecture and sandbox-network diagrams, a detonation timeline, an interactive severity calculator, and a map of every file a case produces.
