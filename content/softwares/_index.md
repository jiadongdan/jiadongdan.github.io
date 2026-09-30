---
title: Softwares
cms_exclude: true

# Superseded by the `code` section, which is what /project-codes/ renders.
# Kept as a source of truth for the two project pages, but not rendered:
# otherwise /softwares/* is a duplicate of /code/* and appears in the sitemap.
# `cascade` propagates the same setting to the child pages (motif-learn, stemplot).
_build:
  render: never
cascade:
  _build:
    render: never
    list: never

# View
view: card

# Optional cover image (relative to `assets/media/` folder).
image:
  caption: ''
  filename: ''
---
