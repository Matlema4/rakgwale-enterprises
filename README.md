# Rakgwale Enterprises — Official Website

> **Learn. Sell. Create. Grow.**  
> South Africa's multi-service platform for tutoring, web development, and reselling opportunities.

---

## 📌 Overview

This is the official single-page website for **Rakgwale Enterprises**, a South African multi-service business offering:

- 🎓 **Academic Tutoring** — Mathematics & Physical Sciences for Grades 7–12
- 💻 **Web Development** — Custom, mobile-responsive websites delivered in 7–14 days
- 🛍️ **Reselling Opportunities** — A flexible income programme for entrepreneurs

The entire site is built as a **single HTML file** (`index.html`) with no external frameworks or build tools required.

---

## 🗂️ File Structure

```
index.html        ← The complete website (HTML + CSS + JavaScript, all-in-one)
README.md         ← This file
```

---

## 🌐 Pages / Sections

The site uses JavaScript-driven page switching (no page reloads). The following pages are included:

| Page | Description |
|---|---|
| **Home** | Hero section, services overview, and stats |
| **About** | Company background and CEO profile |
| **Tutoring** | Subject offerings, session types, and pricing |
| **Web Dev** | Portfolio, process steps, and website request form |
| **Reselling** | Programme details and how to join |
| **Contact** | Contact form with WhatsApp integration |

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and content |
| CSS3 (custom variables) | Styling, animations, and responsive layout |
| Vanilla JavaScript | Page navigation, form handling, admin panel |
| [Google Fonts](https://fonts.google.com) | Playfair Display & DM Sans typefaces |
| [Font Awesome 6.5](https://fontawesome.com) | Icons throughout the site |
| Web Crypto API | SHA-256 password hashing for admin login |

---

## ✨ Features

- **Fully responsive** — works on mobile, tablet, and desktop
- **SPA navigation** — smooth page switching without reloads
- **WhatsApp integration** — contact buttons open pre-filled WhatsApp chats
- **Admin dashboard** — password-protected panel to manage service toggles (demo mode)
- **CEO photo upload** — admin can upload a profile photo, saved via `localStorage`
- **Scroll animations** — elements animate in using the Intersection Observer API
- **Custom SVG logo** — hand-crafted porcupine mascot logo embedded inline
- **Dark navy & gold theme** — consistent brand colour palette via CSS variables

---

## 🔐 Admin Panel

The site includes a hidden admin login accessible from the footer. Credentials are **never stored in plaintext** — they are verified using **SHA-256 hashes** via the Web Crypto API.

> ⚠️ **Security Note:** Because this is a purely client-side site, the hash values are visible in the source code. For production use with sensitive admin access, authentication should be handled server-side.

The admin panel currently operates in **demo mode** — changes reset on page reload.

---

## 🚀 Deployment

No build process is needed. Simply upload `index.html` to any static hosting provider:

| Platform | How to Deploy |
|---|---|
| **Netlify** | Drag and drop `index.html` onto the Netlify dashboard |
| **GitHub Pages** | Push to a repo, enable Pages under Settings → Pages |
| **Vercel** | Import the file and deploy with one click |

All three options are **free**. See the [Netlify docs](https://docs.netlify.com) or [GitHub Pages docs](https://pages.github.com) for more details.

### Optional: Custom Domain
Register a `.co.za` domain (e.g. via [Domains.co.za](https://domains.co.za)) and point it to your hosting provider for a professional South African web address.

---

## 📞 Contact

All enquiries from the website are routed via **WhatsApp**. To update the WhatsApp number, search for `openWhatsApp` in `index.html` and update the phone number in the URL string.

---

## 📄 License

This website and its assets are the property of **Rakgwale Enterprises**. All rights reserved.
