# Hossam Abubakr - Personal Portfolio

A modern, developer-focused personal portfolio built with [Astro](https://astro.build/) and [TailwindCSS](https://tailwindcss.com/). Features a code editor-inspired design with file-based navigation.

## Live Demo

Visit the live portfolio: [hossam.dev](https://hossam.dev)

## About This Portfolio

This portfolio showcases my work as a Software Engineering Team Lead with 8+ years of experience in full-stack development, team leadership, and cloud technologies. The design mimics a code editor interface with file tabs and syntax highlighting.

## Features

- **Code Editor Interface** – File-based navigation with tabs (about.ts, resume.html, README.md)
- **Syntax Highlighting** – Clean code display with Astro's built-in Code component
- **No JavaScript Bundle** – Optimized for performance and speed
- **Fully Responsive** – Mobile-friendly design that works on all devices
- **SEO Optimized** – Complete OpenGraph, Twitter, and DublinCore metadata
- **Personal Content** – Bookshelf, learning journey, and personal interests
- **Professional Showcase** – Technical skills, experience, and achievements

## Tech Stack

- [Astro](https://astro.build/) - Static site generator
- [TailwindCSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Astro Code Component](https://docs.astro.build/en/guides/components/#astro-components) - Syntax highlighting
- [astro-compress](https://github.com/astro-community/astro-compress) - Asset optimization
- [@astrojs/sitemap](https://docs.astro.build/en/guides/integrations-guide/sitemap/) - Sitemap generation

## Getting Started

```sh
# 1. Clone the repository
git clone https://github.com/hossamabubakr/personal-portfolio.git

# 2. Install dependencies
npm install

# 3. Run the development server
npm run dev

# 4. Build for production
npm run build

# 5. Preview the production build
npm run preview
```

## Project Structure

```grep
src/
├── components/
│   ├── ContentAbout.astro      # TypeScript code showcase
│   ├── ContentResume.astro     # HTML resume format
│   ├── ContentReadme.astro     # Personal markdown content
│   ├── Profile.astro           # Profile information
│   └── Contact.astro           # Contact details
├── layouts/
│   └── Layout.astro            # Main layout with SEO
└── pages/
    └── index.astro             # Homepage with tab navigation
```

## Content Sections

### 📄 about.ts

- TypeScript interface showcasing technical skills and experience
- Professional profile with quantified achievements
- Technology stack and expertise areas

### 📄 resume.html  

- Comprehensive resume in HTML format
- Professional experience and career highlights
- Education and technical skills

### 📄 README.md

- Personal learning journey and interests
- Current bookshelf with summaries
- Technologies being learned
- Personal goals and aspirations

## Customization

- Update `src/components/Profile.astro` with your details
- Modify `src/layouts/Layout.astro` for SEO and metadata
- Replace `/src/assets/profile.jpg` with your photo

### Content Updates

- Edit `src/components/ContentAbout.astro` for technical showcase
- Update `src/components/ContentResume.astro` for resume content
- Modify `src/components/ContentReadme.astro` for personal content

### Styling

- Adjust primary color in `tailwind.config.js`
- Customize fonts and spacing in component styles

## ⭐ Contributing

Feel free to fork, customize, and contribute to this project. If you find it useful, leaving a star would be greatly appreciated.
