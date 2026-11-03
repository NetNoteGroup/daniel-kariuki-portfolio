# Daniel Kariuki Githua – Portfolio

A modern, responsive personal portfolio for **Daniel Kariuki Githua**, IT Solutions Architect & Network Engineer based in Kenya, and founder-side showcase of **NetNote Group**.

🔗 **Live site:** https://netnotegroup.github.io/daniel-kariuki-portfolio/

## About

This site presents my experience in networking, CCTV and surveillance systems, server administration, web development, graphic design and technical support, together with my work catalogs and one-tap ways to reach me.

## Features

- Clean, professional single-page design with automatic light and dark mode
- Fully responsive on phones, tablets and desktops
- **NetNote Group** section with the group and subsidiary logos (NetNote Systems, NetNote Security, NetNote Aero)
- **Filterable work catalogs** with tap-to-enlarge images:
  - CCTV & Security
  - Networking
  - Branding & Design
  - Websites & Software
  - Robotics & Drones
- One-tap contact: WhatsApp (pre-filled message), Telegram, Discord, LinkedIn, GitHub, TikTok, email and phone
- Floating WhatsApp chat button
- No frameworks or build step: plain HTML, CSS and a little JavaScript

## Sections

1. Hero with photo and intro
2. About
3. NetNote Group
4. Work catalogs
5. Skills
6. Experience timeline
7. Projects
8. Contact

## Project structure

```
portfolio/
├── index.html        # The whole site (HTML, CSS, JS)
├── photo.jpg         # Profile photo
├── images/
│   ├── cctv/         # CCTV & Security photos
│   ├── networking/   # Networking photos
│   ├── branding/     # Branding & Design work
│   ├── websites/     # Websites & Software screenshots
│   ├── robotics/     # Robotics & Drones photos
│   └── logos/        # NetNote Group logos
└── README.md
```

## Run locally

Open `index.html` in any browser. No installation needed. Keep `photo.jpg` and the `images/` folder next to it.

## Add new work images

1. Resize the image to about 900 px wide and put it in the matching folder inside `images/`.
2. Open `index.html` and find `const WORK=[`.
3. Add one line per image:

```js
{c:"Websites & Software",t:"Client website homepage",s:"images/websites/client-site.jpg"},
{c:"Robotics & Drones",t:"Survey drone prototype",s:"images/robotics/drone-1.jpg"},
```

- `c` is the catalog name and must match exactly (including `&`).
- `t` is the caption.
- `s` is the image path.
- Using a new catalog name creates a new tab automatically.

## Deploy

Works on any static host:

- **Cloudflare Pages / Netlify:** drag and drop the whole folder
- **GitHub Pages:** Settings → Pages → deploy from the `main` branch, root folder

Upload the **whole folder**, not just `index.html`, or the images will not load.

## Contact

- WhatsApp: [+254 798 232 855](https://wa.me/254798232855)
- Telegram: [@Aj_aq9](https://t.me/Aj_aq9)
- Discord: `_aj.01`
- LinkedIn: [Daniel Kariuki](https://www.linkedin.com/in/daniel-kariuki-b25333236/)
- GitHub: [NetNoteGroup](https://github.com/NetNoteGroup)
- TikTok: [@netnote.chronicle](https://www.tiktok.com/@netnote.chronicle)
- Email: kariukid238@gmail.com · netnotechronicles@gmail.com

## License

© 2026 Daniel Kariuki Githua. All rights reserved.
