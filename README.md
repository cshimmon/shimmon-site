# Craig Shimmon – Personal Landing Page

This is a lightweight personal site: a single place for people to find out about me (my work as a digital skills coach and trainer, music, and my background as a recording engineer and music technology lecturer) since I don't really use social media.

The site is designed to be fast, minimal, and easy to maintain, with no frameworks or dependencies.

## 🔗 Live Site

https://shimmon.co.uk

## 📁 Structure

index.html # Main page
style.css # Styling
avatar.jpg # Profile image
robots.txt # Crawler rules
sitemap.xml # Sitemap for search engines


## ⚙️ Tech Stack

- Static HTML & CSS
- SVG icons (from Simple Icons)
- Hosted via Cloudflare Pages
- Source controlled with GitHub

## 🚀 Deployment

This site is automatically deployed via **Cloudflare Pages**.

Any changes pushed to the `main` branch will trigger a new deployment.

## ✏️ Editing the Site

To update the site:

1. Edit `index.html` or `style.css`
2. Commit and push to GitHub
3. Cloudflare Pages will automatically deploy the update

## 🎨 Design Notes

- Clean, Apple-inspired white single-page layout: intro, about tiles (work, music, recording & music tech), interests and grouped links
- Automatic light and dark mode via `prefers-color-scheme`
- Subtle animated level meter under the portrait (disabled for `prefers-reduced-motion`)
- System font stack (San Francisco on Apple devices), so no external requests
- Brand icons (Simple Icons) defined once as an inline SVG sprite and reused with `<use>`
- Colours and spacing live as CSS custom properties at the top of `style.css`

## 📌 Purpose

This site replaces previous hosted link pages and provides:

- Full control over design
- No reliance on third-party platforms
- Faster load times
- Improved reliability

## 📄 License

This project is for personal use. Feel free to use it as inspiration for your own site.
