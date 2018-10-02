# README

Based on the [Xaringan](https://slides.yihui.name/xaringan/#1) R-Markdown slide package, This is a slide template to integrate the Duke University Color Palette

## Combines

* Xaringan slide library ([github](https://github.com/yihui/xaringan) | [vignette](https://github.com/yihui/xaringan))
* [Duke University Color Palette](https://styleguide.duke.edu/color-palette/)

## Info:

My slide-deck template integrates the Duke University Color palette into the Xaringan slide package. Compose your slides in Rmarkdown, knit, and your done. Now go present and deliver the Duke-wow. My next development step for this project is to further integrate the existing template into the Rstudio document template feature-set which will streamline your slide development even more.

## How to Use

1. Follow the Xaringan directions for install and starting a new slide deck

    - `devtools::install_github("yihui/xaringan")`
    - `File -> New File -> R Markdown -> From Template -> Ninja Presentation` (if this doesn't work, see [slide #8](https://slides.yihui.name/xaringan/#8))
    
2. Before you go any further...

    a. copy `duke_slide_template.Rmd` & `duke_color_pallettes_slides.css` to your local slide-composition directory
    b. add 
    
    `css: ["default", "duke_color_pallettes_slides.css"]`
    
    to your YAML header
    
    c. Knit `duke_slide_template.Rmd` to moon_reader
    
    d. Open the duke_slide_template.html in a web browser to learn your next steps.
    
    
I need to make this a package. I'll do it eventually. Till then feel free to collaborate (fork, improve, and submit pull-request) 
   
   
## What does it look like?

- https://www.johnlittle.info/project/custom/slide-template/duke_slide_template.html

## Stray Thoughts

- Trade off: lose a bit of graphical wysiwig for vastly improved reproducibility

- Composed in R-Markdown

- The more you know about CSS the more you can fine-tune the cosmetic layer

- Any opportunity to not use PPT is a good opportunity



