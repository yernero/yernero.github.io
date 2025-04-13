# Personal Portfolio Website

This is my personal portfolio website built with Jekyll and hosted on GitHub Pages. The site showcases my projects, experience, and skills in software development.

## Features

- Clean, responsive design
- Project showcase with detailed descriptions
- Professional resume page
- Contact information and social links
- Mobile-friendly navigation

## Local Development

To run this site locally:

1. Install Ruby and Bundler:
   ```bash
   gem install bundler
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```

4. Visit `http://localhost:4000` in your browser

## Project Structure

- `_config.yml` - Site configuration
- `_includes/` - Reusable components (header, footer)
- `_layouts/` - Page templates
- `projects/` - Individual project pages
- `assets/` - Static assets (images, CSS)
- `*.md` - Content pages

## Adding New Projects

To add a new project:

1. Create a new markdown file in the `projects/` directory
2. Add the following front matter:
   ```yaml
   ---
   layout: project
   title: Project Title
   date: YYYY-MM-DD
   tags: [Tag1, Tag2]
   github: https://github.com/username/repo
   ---
   ```
3. Add project description and details below the front matter

## License

This project is open source and available under the [MIT License](LICENSE). 