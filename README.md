# Alvyl website content

Content for the Alvyl website, edited in [Sveltia CMS](https://sveltiacms.app/en/) (the site's `/admin`
and `/admin/hr` pages). Every save in the CMS is a commit here. This repo holds content only; the
website code lives elsewhere and reads these files when it builds.

```
blog/<slug>.md          blog posts: YAML front matter + Markdown; the file name is the post URL
categories/<slug>.json  blog categories
team/<slug>.json        "Our People" cards; the file name is how a post names its author
images/blog/            images for posts
images/team/            team photos (portrait, 416 × 600 or larger)
```

Edit through the CMS where possible: it keeps the fields and file names in the shape the site expects.
