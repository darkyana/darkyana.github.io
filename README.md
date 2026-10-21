# darkyana.github.io

Personal portfolio of **Annika Yuan** — Senior UX/UI & product designer.

**Live:** <https://darkyana.github.io/>

## What's inside

| Page | Content |
|---|---|
| `index.html` | About — 15+ years of UX/UI, BMW day job, AI-native studio by night |
| `work.html` | Selected work — AI-native products, MyBMW/MINI eCommerce, design system, CCtalk, Cisco Webex |
| `experiments.html` | One-human + AI-agent studio: Star Quiz & Pocket Budget case studies, studio experiments |
| `contact.html` | Contact — email, LinkedIn, GitHub, live products |

## Design

- **Type:** Bricolage Grotesque (display) · Work Sans (body) · Geist Mono (labels) — self-hosted in `fonts/`
- **Color:** deep plum `#5B3A8E` × rose `#B23A67`, with a slowly drifting plum→rose "living gradient" on small accents
- **Hero:** a white sheet with a 1px grid at 5%, dyed by the drifting gradient; a cursor spotlight (170px) trails the pointer and brightens the grid it passes over
- **Zero build:** plain HTML/CSS/JS, no framework, no bundler — deploys as-is

## Structure

```
├── index.html / work.html / experiments.html / contact.html
├── styles.css          # entire design system (OKLCH-free hex tokens, ~700 lines)
├── fonts/              # self-hosted TTFs (SIL OFL)
├── assets/             # app screenshots for case studies
└── .gitignore          # only the deployable site is tracked
```

Working materials (source docs, copy deck, prototypes) live outside the repo in
`input/`, `copy.md`, and `prototype/` — all git-ignored on purpose.

## Local preview

```bash
python3 -m http.server 8642
# → http://localhost:8642/
```

## Deployment

Push to `main` — GitHub Pages rebuilds automatically (~1 min).

## Credits & license

- Code: [MIT](LICENSE) © Annika Yuan
- Site content (copy, screenshots, design): © Annika Yuan — all rights reserved
- Fonts: [Bricolage Grotesque](https://github.com/ateliersmooth/BricolageGrotesque), [Work Sans](https://github.com/weiweihuanghuang/Work-Sans), [Geist Mono](https://github.com/vercel/geist-font) — SIL Open Font License
