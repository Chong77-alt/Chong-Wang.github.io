# Chong-Wang.github.io

## Description

This repository contains the source code for my personal academic homepage. The site is built using Jekyll and is hosted on GitHub Pages. It includes information about my research, publications, projects, and blog posts.

## Building and Deploying the Site

To build and deploy the site locally, follow these steps:

1. **Install Jekyll and Bundler**:
   ```sh
   gem install jekyll bundler
   ```

2. **Clone the repository**:
   ```sh
   git clone https://github.com/Chong77-alt/Chong-Wang.github.io.git
   cd Chong-Wang.github.io
   ```

3. **Install dependencies**:
   ```sh
   bundle install
   ```

4. **Build the site**:
   ```sh
   bundle exec jekyll build
   ```

5. **Serve the site locally**:
   ```sh
   bundle exec jekyll serve
   ```

6. **Deploy the site to GitHub Pages**:
   The site is automatically deployed to GitHub Pages using a GitHub Actions workflow. Any changes pushed to the `main` branch will trigger the deployment process.
