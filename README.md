# Visualizing data in R: Psych 201a in-class practicum

These are the in-class `ggplot2` notebooks for the Week 7 visualization practicum (Thu Nov 12, 2026).

## Before class

1. Clone this repo (or download the ZIP from the green **Code** button) and open the folder in RStudio.
2. Install the packages once:

```r
install.packages(c("tidyverse", "ggthemes", "Hmisc",          # step 1
                   "patchwork", "ggridges", "gapminder",       # step 2
                   "gganimate", "gifski", "png"))
```

## In class, at your own pace

| Notebook | What it covers |
|---|---|
| `ggplot_tutorial.qmd` | Optional warm-up if you've never used ggplot: the grammar of graphics, layers, facets |
| `ggplot_inclass_step1.qmd` | **Start here.** Bar, point, line and scatter plots; error bars (95% CIs); grouping; facets. Practice plots 1–4 |
| `ggplot_inclass_step2.qmd` | Choosing a plot for your data; showing distributions and individual points; customizing labels, legends and themes; saving; multi-panel figures (`patchwork`); debugging; animation. Ends with **your project figure** |

Each practice plot has an empty code chunk followed by the target image. Try to reproduce the target. The `model_figures/` folder has the same target images.

**What to submit:** render whichever notebook you got to (Render button, HTML output) and submit it as described on Canvas.

The last exercise in step 2 is the most useful one: sketch the main figure for your own final project using your pilot or simulated data.

## Credits

The step 1 and step 2 notebooks are adapted from Tobi Gerstenberg's Psych 252 (Stanford) materials. The warm-up tutorial is adapted from Mike Frank's Psych 251 exercise (from Hadley Wickham's `the_grammar.R`). Edited by Bria Long for Psych 201a at UC San Diego.
