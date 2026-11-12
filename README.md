# Maharishi Sacred Spaces

**An immersive brand storytelling website for Eric Swanson — Quantum Spiritual Guide, Author, and Teacher.**

Website: [https://maharishisacredspaces.com/](https://maharishisacredspaces.com/)

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
4. Set the custom domain to `maharishisacredspaces.com`; keep the root `CNAME` file committed.
5. At Porkbun, point the root ALIAS record to `maharishiyeg-lang.github.io`. Alternatively, use A records for `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, and `185.199.111.153`. Point the `www` CNAME to `maharishiyeg-lang.github.io` (no repository path).
6. Remove only conflicting website parking records; preserve email and other unrelated records.
7. Enable **Enforce HTTPS** once GitHub provisions the certificate. The public website is `https://maharishisacredspaces.com/`.

## Social Media

- Instagram: [@maharishi.sacredspace](https://www.instagram.com/maharishi.sacredspace/)
- Instagram: [@maharishisacredspaces](https://www.instagram.com/maharishisacredspaces/)
- Facebook: [Maharishi Sacred Spaces](https://www.facebook.com/maharishisacredspaces)

---

*© Eric Swanson · Maharishi Sacred Spaces · All Rights Reserved*
