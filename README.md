# VCanship Logistics Platform

Welcome to the official repository for the **VCanship Worldwide Logistics Platform**.

---

## 🌍 What is VCanship?

VCanship is a modern, professional logistics platform designed for global shipping, courier, and freight services. It supports **208+ countries** and **132+ languages**, with advanced internationalization, SEO optimization, and a polished user experience out of the box.

---

## 🚀 Features

- **Internationalization:** 208+ countries with flags, currencies, and regional grouping; 132+ languages with automatic switching and fallbacks.
- **Advanced SEO:** Structured data, multilingual sitemaps, hreflang support, robots.txt, and meta tag automation.
- **Modern UI/UX:** Responsive, mobile-first design, dark/light mode toggle, and beautiful gradients.
- **Service Dashboard:** Real-time shipment status, rotating promotional messages, and easy service selection (Express, FCL, LCL, Air Freight).
- **Email Integration:** Amazon SES-ready multilingual transactional emails.
- **Production Ready:** Optimized build, code splitting, and easy deployment to Oracle Cloud, Cloudflare Pages, or your preferred host.

---

## 🛠️ Project Structure

```
vcanship-platform/
├── src/
│   ├── components/
│   ├── data/
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
├── dist/ (production build)
├── public/
├── package.json
├── vite.config.js
└── ...
```

---

## 🚦 Deployment

You can deploy this platform in a few ways:

### 1. **Cloudflare Pages** (Recommended for static hosting)
- Drag and drop your build folder (`dist/`) or connect this repo.
- Follow detailed instructions in `CLOUDFLARE_DEPLOYMENT_GUIDE.md`.

### 2. **Oracle Cloud VPS**
- Use SCP/SFTP or your preferred method to upload the `dist/` folder to your server.
- Configure nginx as described in `IONOS_DEPLOYMENT_GUIDE.md` and `SIMPLE_DEPLOYMENT_INSTRUCTIONS.md`.

### 3. **Other Hosts**
- Any static file server or CDN will work.
- For more details, see the deployment guides in this repo.

---

## 📦 Scripts

- `pnpm install` – Install dependencies
- `pnpm run dev` – Start local development server
- `pnpm run build` – Build for production (output in `dist/`)
- `pnpm run preview` – Preview the production build
- `pnpm run lint` – Lint your codebase

---

## 📈 SEO & Internationalization

- **Structured Data:** Automated with `src/utils/seo.js`
- **Sitemap:** Multi-language, in `public/sitemap.xml`
- **Translation Fallback:** Ensures no missing text, see `src/utils/translations.js`
- **Ready for Google Search Console, Bing, and more!**

---

## 📝 Guides & Documentation

- `CLOUDFLARE_DEPLOYMENT_GUIDE.md`
- `IONOS_DEPLOYMENT_GUIDE.md`
- `DEPLOYMENT_GUIDE.md`
- `SIMPLE_DEPLOYMENT_INSTRUCTIONS.md`
- `SEO_ENHANCEMENT_GUIDE.md`

---

## ❓ Need Help?

- Check the guides above for step-by-step deployment and configuration.
- For technical issues, open an issue in this repo.
- For server and domain problems, refer to your hosting provider's support.

---

## 🏆 Ready to Compete Globally

With VCanship, your logistics business can compete with the world's biggest shipping providers. Launch your international platform today!

---
