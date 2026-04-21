# Madhuri Patil — Portfolio

Built with [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme.

## Local Development

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000

## Deployment

Push to `main` branch on GitHub — GitHub Pages auto-deploys via the `remote_theme` setting.

## Adding your resume PDF

Place your resume at: `assets/MadhuriPatil_Resume.pdf`

## Structure

| Path | Purpose |
|---|---|
| `index.md` | Home page (splash layout with hero, skills, projects) |
| `_pages/work-experience.md` | Experience page |
| `_pages/skills.md` | Skills page |
| `_pages/list.md` | Projects list page |
| `_projects/` | Individual project detail pages |
| `assets/css/custom.css` | All custom styling (cards, badges, grids) |
| `_includes/head/custom.html` | Loads custom.css |
| `_config.yml` | Site-wide settings, author info, skin |
