# mickhayes.github.io

Personal site, built with [Hugo](https://gohugo.io/) and the
[PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme, and published to
GitHub Pages at https://mickhayes.github.io.

Every push to `main` runs `.github/workflows/hugo.yml`, which builds the site and deploys it.

## Get the source

The theme is a Git submodule, so clone with:

```bash
git clone --recurse-submodules https://github.com/mickhayes/mickhayes.github.io.git
```

## Preview locally

Install Hugo **extended** 0.169.0 (the version pinned in the workflow), then:

```bash
hugo server
```

and open http://localhost:1313. Drafts are shown with `hugo server -D`.

## Write a post

```bash
hugo new content posts/my-post/index.md
```

Edit the file, set `draft = false`, commit and push.

## Add a photo gallery

```bash
hugo new content photos/my-trip
```

Copy the photos into `content/photos/my-trip/photos/`. The page already contains
`{{< gallery match="photos/*" >}}`. Hugo makes thumbnails and full-size web versions
at build time, so full-resolution camera files are fine. Captions are optional and go
in the front matter (see `content/photos/street-finds/index.md`).

## Notes

- Comments are disabled site-wide (`params.comments = false`, plus an empty
  `layouts/_partials/comments.html` override).
- The lightbox is [GLightbox](https://github.com/biati-digital/glightbox) 3.3.1,
  stored in `assets/glightbox/`. It loads only on pages that use the gallery.
- To update the theme: `git submodule update --remote themes/PaperMod`.
