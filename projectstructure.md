portfolio/
├── public/                 # Static assets (images, icons, pdf resume)
│   ├── images/
│   ├── favicon.svg
│   └── resume.pdf
│
├── src/
│   ├── components/         # Reusable UI components
│   │   ├── layout/
│   │   │   ├── Navbar.astro
│   │   │   └── Footer.astro
│   │   └── common/
│   │       └── Container.astro
│   │
│   ├── layouts/            # Page layouts
│   │   └── BaseLayout.astro
│   │
│   ├── pages/              # Routes (SSG by default)
│   │   ├── index.astro
│   │   ├── about.astro
│   │   ├── systems.astro
│   │   ├── projects/
│   │   │   └── index.astro
│   │   └── blog/
│   │       └── index.astro
│   │
│   ├── content/            # Markdown / MDX collections
│   │   ├── blog/
│   │   ├── bible/
│   │   ├── learning/
│   │   └── music/
│   │
│   ├── styles/
│   │   └── global.css
│   │
│   └── utils/              # Helpers, constants
│       └── site.ts
│
├── docs/                   # Engineering docs
│   ├── git-playbook.md
│   └── architecture.md
│
├── .github/
│   └── workflows/
│       └── codeql.yml
│
├── astro.config.mjs
├── tsconfig.json
├── package.json
├── README.md
└── .gitignore