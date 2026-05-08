# Song Wang Personal Homepage

This repository contains the Hugo Blox source for [wangsong004.github.io](https://wangsong004.github.io/).

The site presents Song Wang's work in geometry processing, additive manufacturing, targeted dental algorithms, nesting algorithms, and implicit modeling.

## Structure

- `content/home/` contains homepage sections.
- `content/about/` contains the resume-style About page.
- `content/project/` contains portfolio project pages.
- `content/authors/admin/_index.md` stores the primary profile and social links.
- `config/_default/` contains site configuration, menus, SEO, and theme settings.

## Local Build

Install the Hugo Extended version used by the GitHub Pages workflow, then run:

```powershell
hugo server
```

If Hugo Modules are slow to download because direct GitHub access is unstable, set a Go module proxy before building:

```powershell
$env:HUGO_MODULE_PROXY = "https://goproxy.cn,direct"
$env:GOPROXY = "https://goproxy.cn,direct"
hugo --minify --baseURL "https://wangsong004.github.io/"
```

The GitHub Actions workflow builds and deploys the site to GitHub Pages on pushes to `main`.
