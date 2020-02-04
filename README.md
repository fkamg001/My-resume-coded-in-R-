# My CV built using RMarkdown and the pagedown package.
## My pagedown rendered CV

This repo contains the source-code and results of my CV built with the [pagedown package](https://pagedown.rbind.io) and a modified version of the 'resume' template. 

The main files are:

- `Farzam Kamgar's CV.pdf`: The final exported pdf as rendered by Chrome on my mac laptop. 
- `resume.Rmd`: Source template for my resume. 
- `positions.csv`: A csv with columns encoding the various fields needed for a position entry in the CV. A column `section` is also available so different sections know which rows to use.
- `css/`: Directory containing the custom CSS files used to tweak the default 'resume' format from pagedown. 
