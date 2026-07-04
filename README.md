# Kamalakar Marthineni — Portfolio (v3, Aurora)

A single-file, self-contained portfolio site. Maximalist aurora direction with a 3D interactive particle sphere.

## What's in it

- **Aurora background** — 5 large colored orbs slowly drifting and morphing behind everything
- **Cursor spotlight** — a soft violet glow follows your mouse
- **3D particle sphere** in the hero — rotates on its own, tilts to your cursor, 900 colored particles arranged with Fibonacci distribution
- **Glass-morphism cards** with cursor-follow color glow (each project has its own color)
- **Gradient-animated typography** on the name, section titles, and buttons
- **Color-coded sections** — violet, cyan, magenta, gold accents used through experience timeline, project cards, capabilities grid, and stats
- **Star field** with slow parallax
- **Smooth reveal animations** on scroll
- Fully responsive down to ~360px viewport, respects `prefers-reduced-motion`

## Deploy to Vercel (2 minutes)

**Drag & drop (fastest)**
1. Go to [vercel.com/new](https://vercel.com/new)
2. Drop the folder containing `index.html`.
3. Vercel gives you a live URL immediately.

**GitHub + Vercel**
1. Push `index.html` + this README to a new GitHub repo.
2. On [vercel.com/new](https://vercel.com/new), import the repo.
3. Framework: **Other**. Root: `./`. Deploy.

**Reusing `kamalakar-dev.vercel.app`**
- Delete the old Vercel project first, then deploy this one and reuse the name. Or attach a custom domain in Vercel settings.

## Editing

Open `index.html` and search for:
- Name / tagline → `hero-name`
- About text → `about-text`
- Projects → `project-title`
- Experience → `role-title`
- Skills → `cap-title`
- Contact / socials → `contact-links`

## Tech notes

- Fonts: Instrument Serif (display italic), Space Grotesk (body), JetBrains Mono (technical).
- Palette: deep space blue-black with violet, cyan, magenta, gold accents.
- Zero JS dependencies — everything (aurora, cursor, sphere) is vanilla.
- Total weight ~55KB.
