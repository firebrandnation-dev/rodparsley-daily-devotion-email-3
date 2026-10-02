# Rod Parsley Daily Devotion Email Version 3

This repository contains the World Harvest Church branded version of the September 29 Daily Devotion email.

The design follows the current visual system at `https://our.whc.life/`:

- soft lavender page background with white content cards
- WHC purple accents and pale-lavender section dividers
- the official WHC wheat mark
- Georgia display headings inspired by the site's Playfair Display typography
- Calibri body copy for broad email-client support
- the supplied original Rod Parsley Podcast artwork
- the approved devotional and latest-episode content from version 1
- text-only Apple Podcasts, Spotify, and YouTube listening links
- WHC Facebook, Instagram, and YouTube social links
- World Harvest Church calls to action linked to `https://whc.life/`
- clearly separated devotion, podcast, episode, listening, and social sections

Files:

- `index.html` - responsive, table-based HTML email with inline core styling and public HTTPS image URLs
- `plain-text.txt` - matching text-only fallback
- `campaign-notes.txt` - subject, preheader, links, and send notes
- `assets/` - official WHC mark, original podcast artwork, episode thumbnail, and social icons

The core layout is inline-styled and table-based for Gmail, Outlook, Apple Mail, and common campaign tools. Rounded corners degrade to square corners in older Outlook versions without breaking alignment or content. Images use public HTTPS URLs from this repository, so the rendered template can be copied into an email editor without rewriting asset paths.
