# Awesome Jekyll Site

This repo is a basic Jekyll blog used to demo a deployment route of using AWS Amplify and GitHub actions for checking broken HTML.

My [blog post covers the setup steps](https://www.bsmth.de/blog/deploying-jekyll-github-actions-aws-amplify) if you want to start from scratch with a new repository.

## Getting started

If you want to skip creating a new repo and want to try out Jekyll straight away to see how it works, clone the repo and build it like so:

```
git clone git@github.com:bsmth/awesome_jekyll_site.git
cd awesome_jekyll_site
gem install bundler && bundle install
bundle exec jekyll s
```

## Adding new content

The Jekyll repository has a fairly simple structure where top-level pages live as markdown files and new blog posts can be added to the `_posts` directory:

```bash
.
├── 404.html
├── Gemfile
├── Gemfile.lock
├── _config.yml
├── _posts
│   └── 2020-12-23-welcome-to-jekyll.markdown
├── about.markdown
└── index.markdown
```
