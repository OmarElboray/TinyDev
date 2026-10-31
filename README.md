# Tiny Developments

Tiny Developments is a small product studio focused on practical software that gives people more control over their attention, learning, and work.

The repository contains the studio's static website and project showcase.

## Featured projects

- **FreezeTube** — a Chrome extension that reduces YouTube recommendation loops.
- **Hafiz** — a Quran memorization and recitation practice application.
- **NCSS Gateway** — an educational application and review portal.

## Run locally

The site is a static HTML page with no build step:

```bash
git clone https://github.com/OmarElboray/TinyDev.git
cd TinyDev
python -m http.server 8000
```

Open <http://localhost:8000>.

## Repository structure

```text
TinyDev/
├── Index.html   # Studio homepage
├── CNAME        # Custom domain configuration
└── docs/
    └── CNAME    # GitHub Pages configuration for docs
```

## Editing

Project descriptions, links, and contact details are maintained directly in `Index.html`. Replace placeholder links before publishing updates.
