# AI Workshop — Perplexity, Comet & Spaces

A complete interactive workshop website for a 90–120 minute in-person session teaching colleagues how to use Perplexity AI, Comet, and Spaces to accelerate their work. Built for deployment on Vercel via GitHub — no build tools, no npm, no dependencies beyond two CDN scripts.

---

## Repo Structure

- `Index.html` — Main workshop page with all content, polls, and interactive elements
- `poll.html` — Standalone voting page for polls (opens in new tab/window)
- `ReadMe.md` — This file
- `vercel.json` — Vercel deployment configuration

## Features

- **Interactive Polls**: Live-updating polls using JSONBin for data storage
- **Model Simulator**: Compare responses from different AI models
- **QR Code Generation**: Dynamic QR codes for poll links
- **Responsive Design**: Works on desktop and mobile
- **No Dependencies**: Pure HTML/CSS/JS with CDN scripts only

## Deployment

Deployed on Vercel via GitHub integration. Automatic deployments on push.

## Usage

1. Open `Index.html` in a browser or deploy to Vercel
2. Use the polls to gather live feedback
3. Participants vote via `poll.html` (accessible via QR codes)

## Customization

- Update poll questions in `Index.html` (search for POLLS object)
- Modify model responses in the modelResponses object
- Adjust styling in the embedded CSS

