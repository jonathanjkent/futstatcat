+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

title = "FutStat.cat"

# Hero image (optional). Enter filename of an image in the `static/img/` folder.
hero_media = "heroimg.png"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  #color = "#fffad1"
  
  # Background gradient.
   #gradient_start = "#ffccc7"
   #gradient_end = "#ffe7e5"
  
  # Background image.
   image = "catback2.png"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = false

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
#[btn]
#  url = "/authors/admin"
#  label = "Know more"
  


+++
## Projeccions del Futbol Català

Les projeccions aquí es basen en la investigació de [Dixon & Coles](https://rss.onlinelibrary.wiley.com/doi/10.1111/1467-9876.00065). Fem servir [goalmodel.R](https://github.com/opisthokonta/goalmodel) i 10.000 simulacions Monte Carlo dels pròxims partits per projectar els resultats. També fem servir els [soccerbars](https://sn.ethz.ch/research/soccerbars.html) de Ulrik Brandes per visualitzar forma recent. Gràcies a tots!