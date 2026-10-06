# Noman Portfolio

An interactive portfolio website built with Astro, Tailwind CSS, and Rive. The site presents Noman's services, projects, showcase work, and value proposition through responsive sections and interactive sliders.

## Tech Stack

- Astro
- Tailwind CSS
- TypeScript
- Rive canvas animations

## Requirements

- Node.js `22.12.0` or newer
- npm

## Getting Started

Clone the repository and install dependencies:

```sh
git clone https://github.com/Sefatohee/noman-portfolio.git
cd noman-portfolio
npm install
```

Start the development server:

```sh
npm run dev
```

The site will be available at `http://localhost:4321`.

## Available Commands

| Command | Description |
| --- | --- |
| `npm run dev` | Start the local development server |
| `npm run build` | Build the production site into `dist/` |
| `npm run preview` | Preview the production build locally |
| `npm run astro` | Run the Astro CLI |

## Project Structure

```text
src/
├── assets/       Images and project artwork
├── components/   Page sections and interactive UI
├── layouts/      Shared layout components
├── pages/        Astro routes
└── styles/       Global styles
public/           Public files, including the Rive animation
```

## Adding Content

- Add portfolio artwork to `src/assets/`.
- Update the data arrays in `Projects.astro` and `Showcase.astro` when adding cards.
- Replace placeholder card links with project URLs when project pages are available.
- Replace the Rive file in `public/` only when updating the hero animation source.

## Deployment

Build the static site with:

```sh
npm run build
```

Deploy the generated `dist/` directory to a static hosting provider such as GitHub Pages, Netlify, or Vercel.
