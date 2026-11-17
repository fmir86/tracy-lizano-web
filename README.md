# Tracy Lizano - Psychology Consulting

Single-page landing site for a psychology consulting practice, built with Astro 5. Styling uses CSS modules written in SCSS (`src/styles/*.module.scss`) plus Tailwind CSS 4 through its Vite plugin.

## Requirements

- Node.js 20.3 or newer (tested on Node 20.20). Node 18.20.8 and Node 22+ are also supported by Astro 5.
- npm 9.6.5 or newer

## Install

```sh
npm ci
```

## Run

| Command           | What it does                                        |
| :---------------- | :-------------------------------------------------- |
| `npm run dev`     | Starts the dev server at `http://localhost:4321`    |
| `npm run build`   | Builds the static site into `./dist/`               |
| `npm run preview` | Serves the built `./dist/` folder locally           |

The build output is fully static, so `dist/` can be deployed to any static host.

## Project structure

```text
public/
  images/tracy-bot.jpg   hero image
src/
  pages/index.astro      the whole page (header, hero, services, about, testimonials, CTA, footer)
  styles/                one SCSS module per section, plus global.css
```

Fonts load from Google Fonts and some section images load from Unsplash, so the page needs a network connection to look complete.
