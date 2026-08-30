# Mac Vault — Website

This repository contains the **marketing/informational website** for [Mac Vault](https://github.com/ayushcmdx/mac-vault-app) — it is **not** the application itself.

## What this is

A static landing page that showcases Mac Vault: what it does, its features, security model, and installation instructions. Visitors come here to learn about the app and get the install command — no app logic, no authentication, no face recognition code lives in this repo.

## What this is not

This is not the product. For the actual macOS application — the Swift/Xcode source, Core ML face-recognition pipeline, and all the security/auth code — see the main repository:

**→ [ayushcmdx/mac-vault-app](https://github.com/ayushcmdx/mac-vault-app)**

## Structure

```
mac-vault-web/
├── index.html      → Page markup and content
├── styles.css       → All styling
├── app.js           → Scroll animations, tab switching, copy-to-clipboard, etc.
├── assets/          → Logos, screenshots, demo video
└── vercel.json       → Deployment config (caching headers, clean URLs)
```

Plain HTML/CSS/JS — no build step, no framework, no backend.

## Deployment

Hosted on [Vercel](https://vercel.com), deployed directly from this repository.

## License

MIT — see the [main app repository](https://github.com/ayushcmdx/mac-vault-app) for license details.