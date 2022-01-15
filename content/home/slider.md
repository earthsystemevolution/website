---

widget: slider
headless: true  # This file represents a page section.

active: true

# ... Put Your Section Options Here (section position etc.) ...
weight: 15  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 380px


item:
  - title: CausalityTools.jl v1 released
    content: 'CausalityTools is a Julia package for detecting dynamical coupling and causal inference based on time series data.' # 😄
    align: left
    overlay_color: '#555'
    overlay_img: 'earthrise_vis_1092_lrg.png'
    overlay_filter: 0
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Documentation
    cta_url: 'https://juliadynamics.github.io/CausalityTools.jl/stable/'
    cta_icon_pack: fas
    cta_icon: graduation-cap
    cta_new_tab: true

  - title: Predictive asymmetry
    content: "A new method for analysing causality <br> in dynamical systems"
    align: left
    overlay_color: '#333'
    overlay_img: 'predictive_asymmetry_fig.png'
    overlay_filter: 0
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Tutorial
    cta_url: '../project/asymmetrytest/'
    cta_icon_pack: fas
    cta_icon: graduation-cap
    cta_new_tab: true

  - title: What we do
    content: 'We seek new fundamental insights into the coupling between Earth system components. Our approach is to develop and test data-driven techniques for quantifying complex interactions from observed records of natural systems.'
    # Choose `center`, `left`, or `right` alignment.
    align: right
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: '#666'  # An HTML color value.
    overlay_img: plankton_bloom_bottenviken_landsat_april14_2019_cropped.jpg  # Image path relative to your `assets/media/` folder
    overlay_filter: 0  # Darken the image. Value in range 0-1.
    

---