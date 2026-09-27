# Craig Shimmon – Personal Landing Page

This is a lightweight personal site presenting my work as a digital skills trainer and coach, and as an audio and sound specialist, alongside links to my profiles and projects.

The site is designed to be fast, minimal, and easy to maintain, with no frameworks or dependencies.

## 🔗 Live Site

https://shimmon.co.uk

## 📁 Structure

index.html # Main page
style.css # Styling
avatar.jpg # Profile image


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

- Modern single-page layout: hero, services (training & coaching / audio & sound), approach, grouped links and a contact call-to-action
- Automatic light and dark mode via `prefers-color-scheme`
- Animated equaliser motif in the hero (disabled for `prefers-reduced-motion`)
- Fonts: Space Grotesk (headings) and Inter (body) from Google Fonts, with system fallbacks
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
