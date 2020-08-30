---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "test"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2020-08-25T00:20:33-05:00
lastmod: 2020-08-25T00:20:33-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
widget = "slider"  # Use the Slider widget
headless = true  # This file represents a page section.

# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height = "300px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Hello"
  content = "I am center aligned 😄"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "headers/bubbles-wide.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Get Academic"
  cta_url = "https://sourcethemes.com/academic/"
  cta_icon_pack = "fas"
  cta_icon = "graduation-cap"

[[item]]
  title = "Left"
  content = "I am left aligned 😄"
  align = "left"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = ""  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

[[item]]
  title = "Right"
  content = "I am right aligned 😄"
  align = "right"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = ""  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
