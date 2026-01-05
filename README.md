# Technical Blog

A minimalistic technical blog powered by GitHub Pages and Jekyll.

## Setup

1. Create a new repository named `yourusername.github.io` on GitHub
2. Push this code to the repository
3. Go to repository Settings > Pages
4. Set Source to "Deploy from a branch" and select `main` branch
5. Your blog will be available at `https://yourusername.github.io`

## Writing Posts

1. Create a new file in `_posts/` directory
2. Name it: `YYYY-MM-DD-title-of-post.md`
3. Add front matter:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD
   ---
   ```
4. Write your content in Markdown below the front matter

## Local Development

```bash
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000` to preview your blog.

## Customization

- Edit `_config.yml` to update site title, description, and author
- Modify `assets/css/style.css` for styling changes
- Edit layouts in `_layouts/` directory
