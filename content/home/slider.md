---
widget: slider
headless: true  # This file represents a page section.
weight: 1
active: true

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 5000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 300px

item:
  - title: '**Cognitive Psychometrics Lab**'
    content: 'Department of Psychology, National Taiwan University'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: '#666'  # An HTML color value.
    overlay_img: bg-1.jpg  # Image path relative to your `assets/media/` folder
    overlay_filter: 0.9  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    # cta_label: Download my app
    # cta_url: 'https://example.org'
    # cta_icon_pack: fas
    # cta_icon: graduation-cap
  
  - title: Left
    content: 'I am left aligned 😄'
    align: left
    overlay_color: '#555'
    overlay_img: 'bg-2.jpg'
    overlay_filter: 0.9
  
  - title: Right
    content: 'I am right aligned 😄'
    align: right
    overlay_color: '#333'
    overlay_img: 'bg-3.jpg'
    overlay_filter: 0.9
---