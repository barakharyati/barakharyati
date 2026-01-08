# Barak Haryati - Personal Website

A minimal, professional personal website built with Jekyll for GitHub Pages. Clean, fast, and theme-free.

## Quick Start

### Enable GitHub Pages

1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under "Build and deployment":
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or `master`)
   - **Folder**: `/ (root)`
4. Click **Save**

Your site will be live at: **https://barak.haryati.io**

### DNS Configuration (Required)

Configure DNS at your domain registrar for `haryati.io`:

**For subdomain `barak.haryati.io`**, add a CNAME record:

| Type  | Name   | Value                          |
|-------|--------|--------------------------------|
| CNAME | barak  | YOUR-USERNAME.github.io        |

Replace `YOUR-USERNAME` with your GitHub username.

> **Note**: DNS changes can take up to 24 hours to propagate. After DNS is set, GitHub will automatically provision an SSL certificate.

### Customize Your Information

Edit `index.md` to update:

- **LinkedIn**: Replace `YOUR-LINKEDIN-HANDLE` with your actual LinkedIn handle
- **GitHub**: Replace `YOUR-GITHUB-USERNAME` with your GitHub username

## File Structure

```
├── _config.yml           # Jekyll configuration
├── _layouts/
│   └── default.html      # Main HTML layout
├── assets/
│   ├── profile.png       # Profile image
│   └── style.css         # Site styles
├── CNAME                 # Custom domain configuration
├── index.md              # Homepage content
└── README.md             # This file
```

## Customization

### Adding New Sections

Add new sections in `index.md` using this format:

```markdown
---

## Section Title

Your content here.
```

### Adding New Pages

1. Create a new `.md` file (e.g., `blog.md`)
2. Add front matter at the top:

```markdown
---
layout: default
title: Page Title
---

Your page content here.
```

3. Link to it from `index.md` or other pages

### Modifying Styles

Edit `assets/style.css` to customize:

- Colors (CSS variables in `:root`)
- Typography
- Spacing
- Dark mode appearance

## Local Development (Optional)

To preview the site locally before pushing:

### Prerequisites

- Ruby (2.5+)
- Bundler

### Setup

```bash
# Install Jekyll
gem install jekyll bundler

# Run local server
jekyll serve
```

Visit `http://localhost:4000` to preview your site.

### With Bundler (recommended)

Create a `Gemfile`:

```ruby
source "https://rubygems.org"
gem "jekyll", "~> 4.3"
```

Then run:

```bash
bundle install
bundle exec jekyll serve
```

## Features

- ✓ Clean, professional design
- ✓ No external theme dependencies
- ✓ Dark mode support (automatic)
- ✓ Mobile responsive
- ✓ Fast loading (no JavaScript, no external fonts)
- ✓ SEO-friendly

## License

Personal use. Content © Barak Haryati.

