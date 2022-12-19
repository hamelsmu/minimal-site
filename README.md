# Quarto Blog Aggregator

If you write blogs on many different places, but want to collect it in one place with built in stuff for RSS, sorting, filtering, etc - this repo is a minimal example of how.


- `blog/` this has the metadata that will generate the listings on the homepage
  - `blog/meta.yml` will get merged with the front matter in `index.qmd`
  - `blog/blogs.yml` is read by `index.qmd`  and a listing is generated.
