+++
widget = "pages"  
headless = true  
active = true  
weight = 33 

title = "Alumni"
subtitle = ""

[content]
  page_type = "post"
  
  # Choose how much pages you would like to display (0 = all pages)
  count = 3
  
  # Choose how many pages you would like to offset by
  offset = 0

  # Page order. Descending (desc) or ascending (asc) date.
  order = "desc"

  # Filter posts by a taxonomy term.
  [content.filters]
    tag = "Alumni"
    category = ""
    publication_type = ""
    exclude_featured = false
  
[design]
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view = 3
  
[design.background]
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++
