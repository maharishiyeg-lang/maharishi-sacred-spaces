# Maharishi Sacred Spaces

**An immersive brand storytelling website for Eric Swanson — Quantum Spiritual Guide, Author, and Teacher.**

Live site: [https://your-username.github.io/maharishi-sacred-spaces](https://your-username.github.io/maharishi-sacred-spaces)

---

## About

Maharishi Sacred Spaces is a sanctuary of consciousness, sacred tools, and transformative practice. This website serves as the digital home for:

- **The Book** — *Maharishi Sacred Spaces* workbook (digital download + hardcover coming soon)
- **The Meditation** — *The Power Pyramid: The Power of 3* (guided audio, coming soon)
- **Biography** — Eric Swanson's story and teachings

## Color Palette

| Role | Color |
|------|-------|
| Logo Gold | `#C9A84C` |
| Logo Dark Green | `#1A3A2A` |
| Deep Blue | `#0D1B3E` |
| Royal Purple | `#1E0A3C` |
| Accent Gold | `#E8C96A` |

## Pages

- `index.html` — Main landing page (Hero, About, Book, Meditation, Connect)
- `about.html` — Full biography page
- `shop.html` — Sacred offerings / shop page

## How to Update

### Adding Your Book Cover Image
1. Place your cover image in `assets/images/` (e.g., `book-cover.jpg`)
2. In `index.html`, find `id="book-cover-container"` and replace the placeholder `div` with:
   ```html
   <img src="assets/images/book-cover.jpg" alt="Maharishi Sacred Spaces Book Cover" class="book-cover-img" />
   ```

### Adding Your Portrait Photo
1. Place your photo in `assets/images/` (e.g., `eric-swanson.jpg`)
2. Replace the `.about-portrait-placeholder` div with:
   ```html
   <img src="assets/images/eric-swanson.jpg" alt="Eric Swanson" class="about-portrait" />
   ```

### Updating Purchase Links
- Digital download: Search for `href="#connect"` near the book section and replace with your actual download link (Gumroad, Payhip, etc.)
- Hardcover: When available, update the "Coming Soon" badge to a live link

## Deployment (GitHub Pages)

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main → / (root)**
4. Your site will be live at `https://your-username.github.io/maharishi-sacred-spaces`

## Social Media

- Instagram: [@maharishi.sacredspace](https://www.instagram.com/maharishi.sacredspace/)
- Instagram: [@maharishisacredspaces](https://www.instagram.com/maharishisacredspaces/)
- Facebook: [Maharishi Sacred Spaces](https://www.facebook.com/maharishisacredspaces)

---

*© Eric Swanson · Maharishi Sacred Spaces · All Rights Reserved*
