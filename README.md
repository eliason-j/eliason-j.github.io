# eliason-j.github.io

## Attribution
This website was created using [Hugo](https://gohugo.io) and [blogdown](https://cran.r-project.org/package=blogdown). 
Special thanks to Stephen Siegerts for his `hugo-theme-basic` [template](https://github.com/siegerts/hugo-theme-basic), which I used. 
I made extensive use of Yihui Xie's [Creating Websites with R Markdown](https://bookdown.org/yihui/blogdown/) in implementing the theme and in launching the site using Github Pages.
Final acknowledgement to Zach for debugging help and general web dev consulting. 

## Workflow 

This directory is a sub-directory of another directory created using R's `blogdown::build_site()` functionality. 
This structure represents an attempt to follow this advice given [here](https://bookdown.org/yihui/blogdown/github-pages.html).
I'm not sure if this usage is "correct" per se but it seems to be functional, if a little convoluted. I am recording the steps I took in case I forget them down the road.

1. Open the project file (`/Repos/website/public/eliason-j.github.io.Rproj`) in RStudio. 
2. Set the working directory to `/Repos/website/` (one step backwards) and make relevant changes to the website files (i.e. `config.toml`) or create new content using the Blogdown "New Post" add-in in RStudio.
3. Build the site using `blogdown::build_site()`.
4. Stage, commit, push changes. This should all happen in the project opened in step 1, known to RStudio as `public` and which corresponds to the `eliason-j.github.io` Github repository.
5. The website should reflect changes in 30 seconds or so. 

## Changes to style

(Fill in verbose explanation later)

1. Add new css file to static-css
2. Add css file name to config
