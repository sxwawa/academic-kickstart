+++
# A Featured Publications section created with the Featured Content widget.
# This section displays publications from `content/publication/` which have
# `featured = true` in their front matter.

widget = "featured"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 80  # Order that this section will appear.

title = "Featured Publications"
subtitle = ""

[content]
  # Page type to display. E.g. post, talk, or publication.
  page_type = "publication"
  
  # Choose how much pages you would like to display (0 = all pages)
  count = 0

  # Page order. Descending (desc) or ascending (asc) date.
  order = "desc"

  # Show a "See all pages" link underneath the featured content?
  link_to_archive = false

  # Filter posts by a taxonomy term.
  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    author = ""
  
[design]
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view = 3
  
[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
 
 1. Network Together: Node Classification via Cross-Network Deep Network Embedding
 
Network embedding is a highly effective method to learn low-dimensional node vector representations with original network structures being well preserved. However, existing network embedding algorithms are mostly developed for a single network, which fail to learn generalized feature representations across different networks. In this paper, we study a cross-network node classification problem, which aims at leveraging the abundant labeled information from a source network to help classify the unlabeled nodes in a target network. To succeed in such a task, transferable features should be learned for nodes across different networks. To this end, a novel cross-network deep network embedding (CDNE) model is proposed to incorporate domain adaptation into deep network embedding so as to learn label-discriminative and network-invariant node vector representations. On one hand, CDNE leverages network structures to capture the proximities between nodes within a network, by mapping more strongly connected nodes to have more similar latent vector representations. On the other hand, node attributes and labels are leveraged to capture the proximities between nodes across different networks by making the same labeled nodes across networks have aligned latent vector representations. Extensive experiments have been conducted, demonstrating that the proposed CDNE model significantly outperforms the state-of-the-art network embedding algorithms in cross-network node classification.
 
+++
