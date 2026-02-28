# SatisfiesDream Website

A modern, responsive static website for satisfiesdream.in

## Features

- Responsive design
- Smooth scrolling navigation
- Contact form
- GitHub Actions deployment

## Local Development

Open `index.html` in your browser to view the website locally.

## Deployment

This site automatically deploys to GitHub Pages when changes are pushed to the main branch.

### Setup GitHub Pages:

1. Go to your repository Settings
2. Navigate to Pages section
3. Under "Build and deployment", select "GitHub Actions" as the source
4. Push to main branch to trigger deployment

### Custom Domain Setup:

1. In repository Settings > Pages
2. Add your custom domain: `satisfiesdream.in`
3. Configure DNS records with your domain provider:
   - Add A records pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - Or add CNAME record: `<username>.github.io`

## Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Actions workflow
```
