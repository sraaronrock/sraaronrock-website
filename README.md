# sraaronrock.ovh

Personal portfolio website built with [Astro](https://astro.build), TypeScript, and [TailwindCSS](https://tailwindcss.com).

## 🚀 Live

**[sraaronrock.ovh](https://sraaronrock.ovh)**

## ⚡ Tech Stack

- **Framework:** Astro 6
- **Styling:** TailwindCSS 4
- **Language:** TypeScript
- **Hosting:** Cloudflare Workers

## 🛠️ Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 🌐 Deployment

The site is deployed to Cloudflare Workers with the custom domain `sraaronrock.ovh`.

```bash
# Login to Cloudflare (first time only)
npx wrangler login

# Build & deploy
npm run deploy
```

## 📁 Project Structure

```
src/
├── components/
│   ├── Hero.astro            # Profile header with photo and contact info
│   ├── Experience.astro      # Work experience timeline
│   ├── Education.astro       # Education section
│   ├── Certifications.astro  # Professional certifications grid
│   ├── Languages.astro       # Language proficiency bars
│   └── Projects.astro        # Projects section linking to GitHub
├── layouts/
│   └── Layout.astro          # Main layout with nav, footer & theme toggle
├── pages/
│   ├── index.astro           # Homepage
│   └── projects.astro        # Projects page
└── styles/
    └── global.css            # TailwindCSS theme & custom styles
```

## 📝 License

[MIT](./LICENSE)