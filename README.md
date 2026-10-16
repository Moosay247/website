# UEBL Wolves — basketball program website

A responsive website for Chicago's Uptown Elite Basketball League (UEBL) and Wolves AAU program. This repository is the existing site project; the public repository is named `website`.

## What the site includes

- Team galleries for 2018, 2022, 2023, 2024, All-Star events, and camp
- About page covering the league and Wolves AAU program
- Responsive navigation for desktop and mobile
- Animated homepage, media sections, and calendar UI
- Donate page and a shop-coming-soon page
- Cart interface and reusable UI components

The shop's “Notify Me” interaction currently displays a confirmation in the browser; this repository does not show a backend mailing-list integration. The README does not claim that payments or checkout are implemented.

## Stack

Next.js 14, React 18, JavaScript, Node.js, Tailwind CSS, Material UI, Framer Motion, and supporting UI libraries.

## Run locally

Requirements: a compatible Node.js installation and npm.

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000). For a production build:

```bash
npm run build
npm start
```

## Structure

- `src/app/` — pages and route segments
- `src/app/team/` — team and event galleries
- `src/components/ui/` — reusable UI elements
- `public/` — images and videos used by the site

## Project context

Built and maintained for UEBL Wolves, a youth basketball program in Chicago. The site presents program information and team history in one place. Development began in 2024 and is ongoing.

Live site: [ueblwolves.com](https://ueblwolves.com/)
