# News

## Version 3.0
* Adds [markdown image render hook](https://gohugo.io/templates/render-hooks/#image-markdown-example). This should allow you to use Markdown image syntax like `![Alt text](url_to_image.jpg "Title")` to have a single image use glightbox. This should increase compatibility with micro.blog since I believe markdown renders occur prior to shortcode expansion, improving compatiblity with both newsletters and the Photos page. It's also just convenient.

## Version 2.0.8
* Fixes what I did in 2.0.7-- the .File.UniqueID variable requires the page context, e.g. .Page.File.UniqueID.

## Version 2.0.7

* Changes so that all glightbox images have a gallery data property, defaulting to Hugo's unique filename. This should reduce strange gallery collisions on list pages.
* Adds NEWS.md for release notes.
