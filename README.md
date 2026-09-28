# Faryal — Portfolio

A multi-page personal portfolio built with plain **HTML and CSS**. No JavaScript, no frameworks.

**Live site:** https://faryal-intern.netlify.app
**Repository:** https://github.com/faryalrashdi865-crypto/portfolio-for-Tech-SG-internship

## Pages

| File | Purpose |
|---|---|
| `index.html` | Home: intro, services, process, featured project |
| `about.html` | Background and quick facts |
| `skills.html` | Skills, as reusable cards |
| `projects.html` | Projects, as reusable cards |
| `contact.html` | Contact details and a mailto form |
| `style.css` | One shared stylesheet for every page |

## Design decisions

**Built to grow.** Skills, services and projects are repeatable card blocks that share the same CSS classes. Adding a new skill or project means copying one block and editing its text. No CSS changes, no layout work.

**Design tokens.** Colors, radius and max width live as CSS variables at the top of `style.css`, so re-theming is a handful of edits in one place.

**Responsive.** Flexbox and Grid reflow on their own, with breakpoints at 1024px, 768px and 480px.

**Hamburger menu without JavaScript.** A hidden checkbox and a label, styled with the `:checked` sibling selector. It is keyboard accessible: Tab to focus, Space to toggle.

**Accessibility.** Skip-to-content link, visible focus states, `aria-current` on the active page, a logical heading order, and reduced-motion support.

## Adding content

- **New skill:** copy a `.skill-card` block in `skills.html` and edit the text.
- **New project:** copy a `.project-card` block in `projects.html` and edit the text.
- **New service:** copy a `.service-card` block in `index.html` and edit the text.
- **New page:** copy an existing page, then add its link to the nav and footer of each page.

## Running locally

Open `index.html` in a browser. There is no build step.

## Deployment

Hosted on Netlify as a static site.

## Author

**Faryal** — Freelance Web Developer, Pakistan