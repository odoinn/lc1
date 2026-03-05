# Ivy Learning Lab — Website

Static website for Ivy Learning Lab, a Dublin-based learning consultancy. Built for GitHub Pages hosting.

## File Structure

```
ivy-learning-lab/
├── index.html              # Homepage
├── css/
│   └── style.css           # All styles
├── js/
│   └── main.js             # Navigation, tabs, modals, filter, contact form
├── images/
│   ├── training-room.jpg
│   ├── team-laptop.jpg
│   ├── studying.jpg
│   ├── tablet.jpg
│   ├── mobile.jpg
│   ├── professional.jpg
│   └── notetaking.jpg
└── pages/
    ├── about.html          # Team & mission
    ├── services.html       # Tabbed services (Workflow / LXD / Advisory)
    ├── cases.html          # Case studies with modals & filter
    └── contact.html        # Contact form
```

## Deploying to GitHub Pages

1. Create a new GitHub repository (e.g. `ivy-learning-lab`)
2. Upload all files maintaining the folder structure above
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch`
5. Choose `main` branch and `/ (root)` folder
6. Click **Save** — your site will be live at `https://yourusername.github.io/ivy-learning-lab/`

## Colour Palette

| Name       | Hex       | Usage                              |
|------------|-----------|------------------------------------|
| Marigold   | `#FF9A1F` | Primary accent, CTAs, highlights   |
| Yellow     | `#FFD36A` | Secondary accent, tags, borders    |
| Off-white  | `#F4F3EF` | Section backgrounds                |
| Slate      | `#6A6F77` | Muted labels, secondary text       |
| Dark       | `#1C1F24` | Dark sections, body text, buttons  |

## Typography

- **Headings**: Cormorant Garamond (Google Fonts) — elegant serif with italic accents
- **Body**: DM Sans (Google Fonts) — clean, readable sans-serif

## Features

- Fully responsive (mobile-first breakpoints at 960px and 600px)
- Tabbed services page with `?tab=workflow` deep-linking support
- Case study filter (by person / service type) with click-to-open modals
- Accessible keyboard navigation (Escape to close modals)
- Scroll-triggered fade-in animations via IntersectionObserver
- No frameworks or build tools required — plain HTML, CSS, JS
