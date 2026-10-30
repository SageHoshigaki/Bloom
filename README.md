# Bloom / Épanouir Floral Atelier

A responsive five-page frontend rebuilt from the supplied Épanouir reference, using React 19, Vite, Tailwind CSS 4, and Lucide icons.

## Start

```sh
npm install
npm run dev
```

## Production

```sh
npm run build
npm run preview
```

Pages use hash routes: `#/home`, `#/collections`, `#/portfolio`, `#/contact`, `#/consultation`. Static hosting requires no route rewrites.

Includes responsive navigation, collection and portfolio filters, product and project dialogs, a bouquet selection bag, native form validation, FAQs, and demo submission states. Forms and newsletter do not transmit or save submissions; no payment, email, or booking service is connected. Product copy and prices are illustrative.

Original images were supplied from `/Users/maybeeravenn/Documents/Codex/2026-09-07/referenced-chatgpt-conversation-this-is-an/outputs`. Originals are retained in `public/images`, with optimized WebP variants used by the frontend. Typography uses Google Fonts with serif/sans-serif fallbacks.

Source: `src/main.jsx` contains reusable UI components and page views; `src/style.css` includes Tailwind and the responsive design system.
