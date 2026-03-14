# Personal website — Jekyll

A clean  personal website powered by [Jekyll](https://jekyllrb.com/)

## Features

- Sidebar layout with profile photo, affiliation, and social links
- Pages: Home, Resume, Portfolio, Blog
- Responsive design (mobile-friendly)
- Blog with Jekyll posts and excerpts
- No external CSS framework — pure CSS with CSS variables for easy theming

## Project Structure

```
my-personal-website/
├── _config.yml          ← site settings & author info
├── Gemfile
├── _layouts/
│   ├── default.html     ← sidebar + main layout
│   ├── page.html        ← content pages
│   └── post.html        ← blog posts
├── _posts/
│   ├── 2025-01-15-welcome.md
│   └── 2025-03-01-proximal-algorithms.md
├── assets/
│   ├── css/
│   │   └── main.css     ← all styles
│   └── img/
│       └── profile.jpg  ← put your photo here
├── index.md             ← home page
├── resume.md
├── portfolio.md
└── blog.md
```

## Quick Start

### 1. Install Ruby & Jekyll

```bash
# macOS (with Homebrew)
brew install ruby
gem install jekyll bundler

# Ubuntu/Debian
sudo apt install ruby-full build-essential
gem install jekyll bundler
```

### 2. Install dependencies

```bash
cd my-personal-website
bundle install
```

### 3. Customize content

Edit `_config.yml` and fill in your own information:

```yaml
author:
  name: "Fauzan Budi Prasetya"
  email: "fauzan.prasetya@ucla.edu"
  program: "Master's student of Data Science in Health"
  department: "Department of Biostatistics, Fielding School of Public Health"
  university: "University of California, Los Angeles (UCLA)"
  university_url: "https://www.ucla.edu"
  department_url: "https://mdsh.ucla.edu/index.html"
  photo: "assets/img/profile.jpg"   
  github: "https://github.com/fauzanbudi"
  linkedin: "https://linkedin.com/in/fauzan-budi-prasetya"
  cv: "assets/pdf/cv.pdf"    
```

Add your profile photo to `assets/img/profile.jpg`.

Edit the Markdown files (`index.md`, `resume.md`, `portfolio.md`) to reflect your own content.

### 4. Run locally

```bash
bundle exec jekyll serve
# Open http://localhost:4000
```

### 5. Deploy to GitHub Pages

1. Create a repository named `fauzanbudi.github.io` on GitHub.
2. Push this folder's contents to the `main` branch.
3. In the repository **Settings → Pages**, set source to `main / root`.
4. Your site will be live at `https://fauzanbudi.github.io`.

> Tip: you can also use the `github-pages` gem (see the commented line in
> `Gemfile`) to match the exact plugins used by GitHub Pages.

## Customization Tips

| What to change | Where |
|---|---|
| Colour scheme | CSS variables at the top of `assets/css/main.css` |
| Navigation items | `navigation:` list in `_config.yml` |
| Profile sidebar content | `_layouts/default.html` sidebar block |
| Add a new page | Create `newpage.md` with `permalink: /newpage` and add it to `navigation` |
| Add a blog post | Create `_posts/YYYY-MM-DD-title.md` with `layout: post` front matter |
