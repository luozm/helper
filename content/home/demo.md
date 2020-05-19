+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 15  # Order that this section will appear.

title = "HELPeR"
subtitle = "Health e-Librarian with Personalized Recommender (HELPeR)"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  gradient_start = "DarkGreen"
  gradient_end = "ForestGreen"
  
  # Background image.
  image = "dna_bg.png"  # Name of image in `static/img/`.
  image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

Welcome to the **HELPeR**!

This website is the official project site for NIH fund project “Development and Implementation of a Health e-Librarian with Personalized Recommender (HELPeR)”. This is a collaborative project between the School of Nursing and the School of Computing and Information. 

**The overall goal of this proposal is to build and implement a “Health E-Librarian with Personalized Recommendations (HELPeR)” - a personalized information access system with a hybrid recommender engine that adapts to individual aspects of the patient.** This would be the first implementation of a patientcentered system that can serve as a virtual health librarian. The HELPeR recommender engine is innovative in its capacity to integrate three dimensions of an individual patient (i.e., information needs based on the user’s profile, the user’s unique expressed information interests, and the level of user’s disease-related knowledge) to direct patients to highly personalized sets of information, that are high quality, trustworthy, and appropriate for each patient’s knowledge level. As patients select, manage and organize the recommended information, the engine’s capacity for personalization is continuously refined and improved. We have selected ovarian cancer (OvCa) as our initial population as it represents a complex disease with multiple tumor types and a range of prognoses, requiring personalized treatments and supportive care needs that evolve over time28-30. Our team has over 15 years of experience characterizing the needs of women with OvCa across the disease trajectory. 

We have collected and manually curated an extensive e-health library for OvCa patients. HELPeR will filter and recommend information from this library, which will be dynamically adapted for each individual patient.
HELPeR will be housed on a standalone website linked to the OHC of the National Ovarian Cancer Coalition (NOCC). This is one of the most active OvCa OHCs featuring patients’ stories, information, and advice.
HELPeR will also filter and recommend the most relevant discussions found in the NOCC to enhance our curated resource library.
