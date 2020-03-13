+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

title = "Academic"

# Hero image (optional). Enter filename of an image in the `static/img/` folder.
hero_media = "hero-academic.png"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  gradient_start = "#4bb4e3"
  gradient_end = "#2b94c3"
  
  # Background image.
  # image = ""  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
[cta]
  url = "window.open(files/cv.pdf)"
  label = "Download My CV"
  icon_pack = "fas"
  icon = "download"
  
[cta_alt]
  url = "#contact"
  label = "Contact Me"

# Note. An optional note to show underneath the links.
[cta_note]
  label = ''
  
+++

**The Best Way to Create the Website You Want from Markdown (or Jupyter/RStudio)**

Build **Anything** with Widgets

<!-- .social-icon css style for this widget -->
<style>
.social-icon {
  padding: 0px 0px 0px 0px;
  transition: transform .2s; /* Animation */
  width: 40px;
  height: 40px;
  margin: 0 0 10px 5px;
  display: inline-block;
}
.social-icon:hover {
  transform: scale(1.2)
}
</style>

<!-- social icon links -->
<div>
<!--Github-->
<a href="https://github.com/rubensanchezramirez" target="_blank" class="social-icon"><i class="fab fa-lg fa-github"></i></a>
<!--Linkedin-->
<a href="https://www.linkedin.com/in/ruben-sanchez-ramirez-70529a197/" target="_blank" class="social-icon"><i class="fab fa-lg fa-linkedin-in"></i></a>
<!--Email-->
<a href="mailto:rubensanchezramirez@ucsb.edu" target="_blank" class="social-icon"><i class="far fa-lg fa-envelope"></i></a>
</div>
