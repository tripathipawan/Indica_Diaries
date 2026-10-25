# 🔗 Indica Diaries — AllLinks

A clean, premium, and fully responsive link-in-bio page for **Indica Diaries** — a content creation brand sharing stories, ideas and updates from India. Built with pure HTML, CSS, and JavaScript, this single-page site centralizes all social media, newsletters and professional profile links in one shareable URL.

**🔗 Live Demo:** [your-project.vercel.app](https://your-project.vercel.app/)

---

## 📌 Overview

AllLinks is a custom-built alternative to tools like Linktree, designed specifically for the Indica Diaries brand. It presents a branded, visually cohesive landing page with the golden Indica Diaries emblem, tagline, and direct links to all active platforms — YouTube, Instagram, WhatsApp Channel, Facebook, X (Twitter), LinkedIn, Substack, and two LinkedIn newsletters.

The page is intentionally lightweight with no frameworks — no npm, no build step. Open `index.html` and it works.

---

## ✨ Features

- **Branded Profile Header** — Displays the Indica Diaries logo in a glowing circular emblem, the brand name, and the tagline ("Stories, ideas and updates from India") at the top of the page for immediate visual identity.
- **9 Platform Links** — Direct, clickable links to all active social, newsletter and professional profiles: YouTube, Instagram, WhatsApp Channel, Facebook, X (Twitter), LinkedIn, Substack, Indica Diaries Newsletter and Tech Eden Newsletter — all opening in a new tab.
- **Featured Primary Link** — The first link (YouTube) is highlighted as a large gradient button so visitors see the main channel first.
- **Premium Pink Theme** — Soft blush-pink aurora background, glass-style link cards, rose-to-magenta gradients and a deep plum text color for a polished, premium look.
- **Hover Animations** — Smooth card lift, a soft light that follows the cursor, a shine sweep on the featured button and animated icon tiles for an interactive feel.
- **Fully Responsive Layout** — A single column on mobile, a two-column link grid on tablet, and a split layout on desktop (brand intro on the left, links panel on the right). Optimized for mobile-first usage since link-in-bio pages are primarily opened on phones.
- **Share Button** — A "Share this page" button opens the native share sheet on phones and copies the link to the clipboard on desktop.
- **Easy to Edit** — All links live in one `LINKS` array inside `index.html`. Add, remove or reorder a link by editing a single block of code.
- **Accessible** — Semantic HTML, keyboard focus styles, and reduced-motion support for users who prefer less animation.
- **Vercel Ready** — Static files only, so it deploys to Vercel in seconds with automatic HTTPS and global CDN delivery.
- **Shareable Single URL** — The entire page is designed to be shared as one link — ideal for social media bios, email signatures, and business cards.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure, semantic layout, anchor links |
| CSS3 | Custom styling, glass effects, hover animations, responsive design, brand theming |
| JavaScript (ES6) | Rendering the link list, cursor-follow light effect, share and copy-link behavior |
| Google Fonts | Plus Jakarta Sans typography (falls back to system fonts if unavailable) |
| Vercel | Deployment and global CDN hosting |

---

## 📁 Project Structure

```
AllLinks/
├── index.html        # Main page — HTML structure, CSS styling and JavaScript in one file
├── logo.png          # Indica Diaries emblem (circular, used in header and as favicon)
└── README.md         # Project documentation
```

---

## 🚀 Getting Started

No installation or build step required.

**1. Clone the repository**
```bash
git clone https://github.com/tripathipawan/YOUR-REPO-NAME.git
```

**2. Navigate into the project folder**
```bash
cd YOUR-REPO-NAME
```

**3. Open the page**

Simply open `index.html` in any modern browser — or use the VS Code **Live Server** extension for a better development experience:

```
Right-click on index.html → Open with Live Server
```

---

## ✏️ Customizing Links

All links are defined in the `LINKS` array near the bottom of `index.html`. To add a new platform, copy one entry and change its values:

```js
{
  name: "Platform Name",
  sub:  "Short description",
  url:  "https://example.com/your-profile",
  icon: '<path d="..."/>'   // SVG shapes drawn inside a 24x24 viewBox
}
```

The first entry in the list is displayed as the large featured button.

---

## 🎯 Platform Links Included

| Platform | Link |
|---|---|
| YouTube | [@indicadiaries](https://youtube.com/@indicadiaries) |
| Instagram | [@indicadiaries.in](https://www.instagram.com/indicadiaries.in) |
| WhatsApp Channel | [Indica Diaries Channel](https://whatsapp.com/channel/0029Vb7sg2V3bbV4NpadBX1m) |
| Facebook | [Indica Diaries](https://www.facebook.com/share/1K1sHVWRcy/) |
| X (Twitter) | [@Indicadiaries](https://x.com/Indicadiaries) |
| LinkedIn | [Pawan Tripathi](https://www.linkedin.com/in/pawantripathi/) |
| Substack | [@indicadiaries](https://substack.com/@indicadiaries) |
| Indica Diaries Newsletter | [LinkedIn Newsletter](https://www.linkedin.com/newsletters/indica-diaries-7519989539940110336/) |
| Tech Eden Newsletter | [Developer Insights](https://www.linkedin.com/newsletters/tech-eden-developer-insights-7483395366604800000/) |

---

## 🌱 What I Learned

- Building a production-ready, branded static page without any frameworks or build tools
- Designing a responsive layout that adapts from mobile to tablet to a split desktop view using CSS Grid and media queries
- Creating premium UI effects such as glassmorphism, gradients and cursor-follow hover lighting with pure CSS and JavaScript
- Preparing a logo for the web (circular crop, optimized size) so it renders sharply everywhere
- Deploying a static site to Vercel with automatic HTTPS and global CDN

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature-name`)
3. Commit your changes (`git commit -m 'Add: your feature description'`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Open a Pull Request

---

## 👨‍💻 Author

**Pawan Tripathi**
- GitHub: [@tripathipawan](https://github.com/tripathipawan)
- LinkedIn: [Pawan Tripathi](https://www.linkedin.com/in/pawantripathi/)
- Live Brand: [Indica Diaries on YouTube](https://youtube.com/@indicadiaries)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
