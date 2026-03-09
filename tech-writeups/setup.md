# tech-writeups

Markdown-based technical writeups powered by **mdBook**.

## 1) Local setup

```bash
cargo install mdbook --locked
```

## 2) Local preview

```bash
cd tech-writeups
mdbook serve --open
```

## 3) Build static site

```bash
cd tech-writeups
mdbook build
```

Output directory: `tech-writeups/book/`

## 4) Deploy to GitHub Pages

This repository includes a workflow at `.github/workflows/deploy-mdbook.yml`.

- Push to `main`
- GitHub Actions builds the book
- Artifact is deployed to GitHub Pages

Then enable Pages in repository settings (Build and deployment: **GitHub Actions**).
