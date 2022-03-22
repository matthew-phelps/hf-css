# hf-css

Project contains CSS files for Hjerteforenings shiny-apps. The idea was to have a central place to keep all the CSS stylings for Hjerteforenings Shiny apps, that way I could make changes in one central place, instead of in each app.

### 1. css-main.css
This file contains the base css that is common to all Hjerteforeningen shiny apps. DO NOT MAKE CHANGES in this file without verifying and testing that all the dependent apps function as they should. For a list of these dependent apps, look at the app-specific css files below

### 2. App-specific css files
These files contain all the css that is specific to each app. This usually is limited to element ID references.
- ht-css.css (used for HjerteTal and LMH apps).
- Other CSS files were for projects that have been killed (e.g. the stroke-risk calculator)
