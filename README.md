# React + Tailwind Admin Dashboard Template

A responsive admin dashboard UI built with **React 18**, **Vite**, and **Tailwind CSS**. It ships a single polished dashboard layout plus a library of reusable, copy-paste UI components — charts, tables, forms, cards, dropdowns, switchers, a calendar, profile/settings pages, and authentication screens.

> Frontend only: this is a presentation/UI template. There is no backend, no API integration, and no data persistence — the auth screens and tables are static UI.

**Live demo:** https://admin-dashboard-template-beryl.vercel.app/

## Screenshot

<!-- Add a screenshot of the dashboard here -->
![Dashboard screenshot](./screenshot.png)

## Tech stack

- React 18
- Vite 4 (dev server + build)
- Tailwind CSS 3 (+ PostCSS, Autoprefixer)
- React Router 6
- ApexCharts (via `react-apexcharts`) for charts
- jsVectorMap for the map widget

## Features

- Dashboard layout with sidebar, header, and dark-mode toggle
- Reusable components: stat cards, charts, data tables, dropdowns, checkboxes, switchers
- Form elements and form-layout pages
- Auth screens (Sign In / Sign Up) — static UI
- Calendar, Profile, Settings, and UI-element showcase pages
- Self-hosted Satoshi font

## Getting started

Requires Node.js 14.16+ (npm included).

```bash
# install dependencies
npm install

# start the dev server (http://localhost:5173)
npm run dev
```

## Production build

```bash
npm run build     # outputs to /dist
npm run preview   # preview the production build locally
```

Upload the contents of `/dist` to any static host (Vercel, Netlify, GitHub Pages, etc.).

## Project structure

```
src/
  components/   reusable UI components (cards, charts, tables, dropdowns…)
  pages/        page-level views (Dashboard, Auth, Forms, Tables, Settings…)
  layout/       app shell / default layout
  hooks/        custom hooks (color mode, local storage)
  images/ fonts/ js/   static assets
```

## Credits

Based on the open-source [TailAdmin](https://tailadmin.com) free React template.

## License

Released under the MIT License. See [LICENSE](./LICENSE).