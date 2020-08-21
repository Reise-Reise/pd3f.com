+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

title = "pd3f – Beyond PDF"

# Hero image (optional). Enter filename of an image in the `static/media/` folder.
hero_media = "logo_margin.svg"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "#4bb4e3"
  # gradient_end = "#2b94c3"
  
  # Background image.
  image = "cover.jpg"  # Name of image in `static/media/`.
  image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
[cta]
  url = "https://demo.pd3f.com"
  label = "Try out the demo"
  icon_pack = "fas"
  icon = "file-upload"
  
[cta_alt]
  url = "/examples"
  label = "View Examples"

# Note. An optional note to show underneath the links.
# [cta_note]
#  label = '<span class="js-github-release" data-repo="gcushen/hugo-academic">Show your product version here:<!-- V --></span>'
+++


pd3f is an Open-source PDF **text extraction** pipeline that is self-hosted, local-first and Docker-based.

pd3f **reconstructs** the original **continuous text** with the help of **machine learning**.

pd3f is still in an experimental stage, so please use it with caution.
