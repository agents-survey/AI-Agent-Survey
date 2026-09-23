# Toward Useful Systems for Useful Agentic AI

A collaborative research initiative website featuring over 20 researchers across UC Berkeley, Stanford, IBM Research, UIUC, and Intesa Sanpaolo.

## 🌐 Live Site
Visit: https://agents-survey.github.io/AI-Agent-Survey/

## 📋 Features
- **Research Areas**: Key focus areas in agentic AI systems
- **Team Directory**: 20+ researchers across 5 institutions
- **Event Management**: Workshops, summits, and research activities
- **Participation Portal**: Surveys, interviews, and collaboration opportunities
- **Responsive Design**: Professional layout optimized for all devices

## 🚀 Local Development
If you have Ruby and Bundler installed:

```bash
bundle install
bundle exec jekyll serve
```

Then open [http://localhost:4000/AI-Agent-Survey/](http://localhost:4000/AI-Agent-Survey/) (the site uses `baseurl: "/AI-Agent-Survey"`).

## 📁 Site Structure
- `index.md` - Homepage: photo hero, partner logos, mission, research areas, latest events and a call to action
- `about.md` - About the research collaboration
- `team.md` - Team directory by institution
- `events.md` - Events, workshops, and speaking opportunities
- `participate.md` - Research participation: survey, expert interviews, sharing work
- `_config.yml` - Site configuration and metadata, including the announcement bar text
- `_data/navigation.yml` - Menu entries (also used by the "Explore" column of the footer)
- `_includes/masthead.html` - Announcement bar, navigation and breadcrumb
- `_includes/footer.html` - Multi-column footer (replaces the theme footer)
- `_includes/head/custom.html` - Highlights the current page in the menu
- `_layouts/default.html` - Page layout (overrides the theme layout)
- `assets/css/main.scss` - All custom styles
- `assets/images/` - Logos

## 🎨 Styling
All custom styles live in `assets/css/main.scss`, organized in numbered sections (palette, theme settings, layout, header, footer, shared components, page-specific styles).

- **Colors**: use only the [UC Berkeley palette](https://brand.berkeley.edu/visual-identity/colors/) variables defined at the top of the file (`$berkeley-blue`, `$california-gold`, …). To add a color, pick it from that page and add it to the palette first.
- **No inline styles**: build pages from the shared components instead:
  - `split-card` (image + text, used as page intro; `split-card--light` for a gray version)
  - `section-header` (section title and intro text)
  - `band` (full-width section; `band--light` for gray, `band--blue` for blue)
  - `feature-grid` + `feature-card` (`--blue`, `--darkblue`, `--gold`, or `--white` for photo cards)
  - `actions` (centered row of buttons: `btn--primary`, `btn--success`, `btn--outline-gold` on dark backgrounds)
  - `arrow-link` / `arrow-links-list` (text links with an arrow)
- **Layout inspiration**: the [UC Berkeley EECS website](https://eecs.berkeley.edu).
- **Photos**: from [Unsplash](https://unsplash.com), linked directly from `images.unsplash.com`.

## 🛠 Built With
- **Jekyll** with Minimal Mistakes theme
- **GitHub Pages** for hosting
- **Custom SCSS** for Berkeley branding
- **Font Awesome** for icons

## 🔗 Quick Links
- [Participate in Research](https://agents-survey.github.io/AI-Agent-Survey/participate/)
- [Meet the Team](https://agents-survey.github.io/AI-Agent-Survey/team/)
- [View Events](https://agents-survey.github.io/AI-Agent-Survey/events/)
- [About the Project](https://agents-survey.github.io/AI-Agent-Survey/about/)
