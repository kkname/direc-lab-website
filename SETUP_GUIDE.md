# DiReC Lab Website Setup Guide

## Overview
This is your new DiReC Lab website built with Hugo and the Hugo Blox Research Group theme. The site features a bright, modern color scheme designed specifically for your lab.

## What's Been Configured

### 1. Site Information
- **Title**: DiReC Lab - Digital Innovation and Research in Construction
- **Theme**: Custom bright theme with sky blue primary colors (#0ea5e9)
- **Layout**: Research group template with sections for Home, People, Research, Publications, News, and Contact

### 2. Custom Features
- **Bright Color Scheme**: Custom theme file at `data/themes/direc_bright.toml`
- **Research Focus Areas**: Four core research areas displayed on homepage
  - Project Intelligence
  - Data Interoperability
  - Workforce Solutions
  - Educational Tools

### 3. Contact Information
- Location: Francis Hall, Texas A&M University, College Station, TX
- Director's office: Room 321B
- Research team office: Room 328

## Viewing Your Site

The website is currently running at: **http://localhost:1313/**

Open this URL in your web browser to see your site!

## Next Steps

### Customize Content

1. **Add Team Members**: Edit files in `content/authors/` or create new author profiles
2. **Add Publications**: Add publication files in `content/publication/`
3. **Add News/Posts**: Create news items in `content/post/`
4. **Update Images**: Replace images in `static/` and `assets/media/`

### Customize Appearance

1. **Colors**: Edit `data/themes/direc_bright.toml` to adjust the color scheme
2. **Homepage**: Edit `content/_index.md` to modify homepage sections
3. **Logo**: Add your lab logo to `assets/media/` and update config

### Key Files to Know

- `config/_default/hugo.yaml` - Main site configuration
- `config/_default/params.yaml` - Site parameters and theme settings
- `config/_default/menus.yaml` - Navigation menu configuration
- `content/_index.md` - Homepage content
- `content/contact/index.md` - Contact page
- `data/themes/direc_bright.toml` - Custom bright color theme

## Common Commands

```bash
# Start development server
cd /Users/yizhi/direc-lab
hugo server -D

# Build site for production
hugo

# Update modules
hugo mod get -u
```

## Adjusting Colors

To make the site brighter or change colors, edit `data/themes/direc_bright.toml`:

```toml
[light]
  primary = "#0ea5e9"          # Main accent color
  primary_light = "#38bdf8"    # Lighter variant
  primary_dark = "#0284c7"     # Darker variant
  background = "#ffffff"       # Page background
  background_2 = "#f1f5f9"     # Alternate background
```

Some bright color suggestions:
- Sky Blue (current): `#0ea5e9`
- Teal: `#14b8a6`
- Emerald: `#10b981`
- Amber: `#f59e0b`
- Rose: `#f43f5e`

## Documentation

- Hugo Blox Documentation: https://docs.hugoblox.com/
- Hugo Documentation: https://gohugo.io/documentation/

## Support

For issues with the Hugo Blox theme, visit: https://github.com/HugoBlox/hugo-blox-builder
