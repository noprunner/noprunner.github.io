# Security Research Blog

Retro terminal-themed Jekyll blog for security research, penetration testing, and HackTheBox write-ups.

## Theme Features

- **Retro Terminal Aesthetic**: Matrix-style green on black with monospace fonts
- **Content-Focused**: Minimal personal info, posts take center stage
- **Security-Oriented**: Optimized for code snippets, command examples, and technical write-ups

## Local Development

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# Visit http://localhost:4000
```

## GitHub Pages Deployment

This site is configured for automatic deployment to GitHub Pages.

### Setup Instructions:

1. **Create GitHub Repository**:
   - Create a new repository named: `noprunner.github.io`
   - Make it public (required for free GitHub Pages)

2. **Enable GitHub Pages**:
   - Go to repository: `Settings > Pages`
   - Source: `GitHub Actions`

3. **Push Your Changes**:
   ```bash
   git add .
   git commit -m "Configure retro security blog theme"
   git push origin master
   ```

4. **Monitor Deployment**:
   - Go to `Actions` tab in your GitHub repository
   - Wait for the workflow to complete
   - Your site will be available at: `https://noprunner.github.io`

## Adding New Posts

Create new posts in the `_posts/` directory with the format:

```
YYYY-MM-DD-post-title.markdown
```

Example frontmatter:
```yaml
---
layout: post
title:  "HTB: Machine Name Walkthrough"
date:   2026-01-29 12:00:00 +0300
categories: htb pentesting
---
```

## Customization

- **Colors**: Edit `/css/main.scss` variables
- **Layouts**: Modify files in `_layouts/`
- **Styles**: Update SCSS files in `_sass/`
- **Config**: Edit `_config.yml` for site-wide settings

## Tips

- Use code blocks extensively - they're styled for terminal/hacking aesthetic
- H2 and H3 headings automatically get `##` and `###` prefixes
- Links glow on hover for that cyberpunk feel
- Post listings have `[+]` prefixes and hover effects

Happy hacking! 🔐
