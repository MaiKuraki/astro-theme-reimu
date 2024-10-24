<img src="https://fastly.jsdelivr.net/gh/D-Sketon/astro-theme-reimu@main/screenshot.png"/>
<div align = center>
  <h1>astro-theme-reimu</h1>
  <img alt="GitHub License" src="https://img.shields.io/github/license/D-Sketon/astro-theme-reimu">
  <img alt="FOSSA Status" src="https://app.fossa.com/api/projects/git%2Bgithub.com%2FD-Sketon%2Fastro-theme-reimu.svg?type=shield"/>
  <p align="center">
  ❤ Hakurei Reimu ❤
  </p>

  [Demo](https://d-sketon.github.io/astro-theme-reimu)

  [简体中文](https://github.com/D-Sketon/astro-theme-reimu/blob/main/README.md) │ English
</div>

Based on [hexo-theme-reimu](https://github.com/D-Sketon/hexo-theme-reimu) migrated [Astro](https://astro.build) blog theme

**ISSUE and PR Welcome!**

## Lighthouse

<p align="center">
  <a href="https://pagespeed.web.dev/analysis/https-d-sketon-github-io-astro-theme-reimu/ur4yncrgnm?form_factor=desktop">
    <img width="710" alt="astro-theme-reimu Lighthouse Score" src="https://fastly.jsdelivr.net/gh/D-Sketon/astro-theme-reimu/psi.svg">
  <a>
</p>

## Project structure
```txt
/
├── public/
│   ├── images/
│   │   └── banner.webp
│   │   └── banner-800w.webp
│   │   └── banner-600w.webp
│   │   └── favicon.ico
│   │   └── reimu.png
│   │   └── taichi.png
│   └── robots.txt
├── src/
│   ├── components/
│   ├── content/
│   │   │  blog/
│   │   │    └── some-blog-posts.md
│   │   └── config.ts
│   ├── hooks/
│   ├── languages/
│   ├── layouts/
│   └── pages/
│   │   └── about.mdx
│   └── styles/
│   └── utils/
│   └── config.yml
│   └── covers.yml
│   └── env.d.ts
└── package.json
```

Any static assets (such as images) can be placed in the `public/` directory.
All blog posts are stored in the directory `src/content/blog` and `about` page are stored in the directory `src/pages`.

## Usage
```bash
git clone https://github.com/D-Sketon/astro-theme-reimu.git
cd ./astro-theme-reimu

pnpm i
pnpm run dev
```

## Feature
- ✅ SEO-friendly
- ✅ Night Mode
- ✅ Fuzzy search
- ✅ Tag Archives
- ✅ Sitemap && RSS
- ✅ Commenting System (Valine / Waline / Gitalk)
- ✅ LaTeX support
- ✅ Mermaid support
- ✅ busuanzi / Reading Statistics (Valine / Waline)
- ✅ Friendship Cards
- ✅ Internationalization
- ✅ Baidu Analytics/Google Analytics/Microsoft Clarity

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FD-Sketon%2Fastro-theme-reimu.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FD-Sketon%2Fastro-theme-reimu?ref=badge_large)