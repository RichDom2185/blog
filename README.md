# Richard's Blog

Source code for my blog, powered by [Jekyll](https://jekyllrb.com/).

## Setting up

Make sure you have Ruby 2.7 installed. Then run:

```bash
bundle install
```

This will install your dependencies locally under the `.bundle` directory.

To start the server, run:

```bash
bundle exec jekyll serve --livereload
```

## Deployment

Blog is automatically generated from the `main` branch using GitHub Pages. The `_redirects` file is used solely for the staging deployment on Netlify.
