# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static GitHub Pages website (cbivo76.github.io) serving as a tourist guide for Timisoara, Romania, under the domain touristtm.com. The site is maintained by Cristian Bivolaru and provides German-language information about visiting Timisoara.

## Architecture

**Static Website Stack:**
- Pure HTML/CSS/JavaScript (no build process required)
- GitHub Pages hosting with custom domain (touristtm.com via CNAME)
- Theme based on "orderedlist" GitHub Pages theme
- Google Analytics tracking (UA-58521389-1)

**Key Components:**
- `index.html` - Main landing page with Timisoara guide content in German
- `stylesheets/` - Theme CSS files (styles.css, stylesheet.css, pygment_trac.css)
- `javascripts/` - Minimal JS for mobile viewport handling (scale.fix.js)
- `images/` - Theme assets
- `portrait.png` - Photo of Cristian Bivolaru
- `params.json` - Legacy configuration file (appears to be from previous site owner/content)
- `profile.ttl`, `profileStarwars.ttl` - RDF/FOAF semantic web profile data

## Content Structure

The main content is entirely in German and covers:
- Timisoara's baroque architecture and historical significance
- Tourist attractions (Piața Unirii, Piața Victoriei, parks, etc.)
- Dining and cultural recommendations
- Transportation and practical travel tips
- Contact information for guide services

## Deployment

Changes pushed to the `main` branch are automatically deployed via GitHub Pages. No build or deployment commands needed.

## Making Changes

**To update content:**
- Edit `index.html` directly for page content
- Modify CSS files in `stylesheets/` for styling changes
- All changes take effect immediately on push to main branch

**Domain configuration:**
- Custom domain configured via `CNAME` file (touristtm.com)
- Do not remove or modify CNAME unless changing domain

## Notable Details

- RDF profile files suggest potential future semantic web integration
- Mobile-optimized via scale.fix.js for iPhone gesture handling
- All tracking configured for UA-58521389-1 Google Analytics property
