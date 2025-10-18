# Personal Website

A personal website built with Jekyll and hosted on GitHub Pages.

## Features

- Home page with introduction and contact links
- Resume page with experience, education, and skills
- Projects collection with individual project pages
- Blog with posts

## Local Development

1. Install dependencies:
   ```bash
   bundle config set --local path 'vendor/bundle'
   bundle install
   ```

2. Run the site locally:
   ```bash
   bundle exec jekyll serve
   ```

3. Visit `http://localhost:4000` in your browser

## Deployment to GitHub Pages

1. Create a new repository on GitHub (e.g., `username.github.io`)
2. Initialize git and push your code:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/username/username.github.io.git
   git push -u origin main
   ```

3. Go to your repository settings → Pages
4. Set source to `main` branch
5. Your site will be live at `https://username.github.io`

## Customization

- Update `_config.yml` with your personal information
- Edit content in `index.md`, `resume.md`
- Add your projects to `_projects/` folder
- Write blog posts in `_posts/` folder
- Customize styling in `assets/css/style.css`

## Structure

```
├── _config.yml          # Site configuration
├── _layouts/            # HTML layouts
├── _posts/              # Blog posts
├── _projects/           # Projects collection
├── assets/css/          # Stylesheets
├── index.md             # Home page
├── resume.md            # Resume page
├── projects.md          # Projects listing
├── blog.md              # Blog listing
└── Gemfile              # Ruby dependencies
```
