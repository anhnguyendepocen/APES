Overview for contributors
===

## How to make changes / contribute content

#### Reporting problems

* If you see a problem or if you have a suggestion, log in to GitHub and report the issue at [here](https://github.com/biometry/APES/issues). Issues can also be assigned to someone in particular

#### Adding content

Ordered with increasing technical demands, and decreasing work for us. Please choose the highest number you're comfortable with, this will reduce our workload

1. Write your text as .txt or .rtf or .md and send it to  [Eng. Andrea Janeiro](https://www.biom.uni-freiburg.de/mitarbeiter/janeiro)
2. Clone our repository, change the text, and issue a pull request so that we can include your changes 
3. Ask for direct access to the repo

#### Important!!!!

* html links in md within the site should be to the html version of the page, the two versions have different roots, it's not possible to set relative paths


## Help with R markdown

We use R markdown to write the text for this site. 

"R Markdown is an authoring format that enables easy creation of dynamic documents, presentations, and reports from R. It combines the core syntax of markdown (an easy-to-write plain text format) with embedded R code chunks that are run so their output can be included in the final document. R Markdown documents are fully reproducible (they can be automatically regenerated whenever underlying R code or data changes)." ( [http://rmarkdown.rstudio.com/](http://rmarkdown.rstudio.com/) )

If you start working with R markdown, you will see that it's extremely simple and very similar to wiki syntax you might be used to. Have a look at 

* [Getting Started with R Markdown, knitr, and Rstudio](http://jeromyanglim.blogspot.de/2012/05/getting-started-with-r-markdown-knitr.html)
* https://support.rstudio.com/hc/en-us/articles/200552086-Using-R-Markdown
* You can also try some online markdown editors  e.g. [`StackEdit Viewer`](https://stackedit.io/editor)  and [https://jbt.github.io/markdown-editor/](https://jbt.github.io/markdown-editor/).

### Page maintainer and contributors

You can ask to be assigned as a maintainer of one or more pages of your choice to keep them up to date.
If you prefer, you can only be set up as a contributor.

## Special tasks

### Code

We use chunks to display our codes. The chunks can be manually added by writting
```

```{r} code ```
```


Or inserted automaticly by clicking on the chunk button at the top right corner of the script window.
Some extra info about R Code Chunks:

* http://rmarkdown.rstudio.com/authoring_rcodechunks.html

### Images 

To add an image, save the image on the folder /img/ and commit it. Once on the repo, you can copy the raw version of the image and add it to the markdown, e.g:

```
![My image] (username.github.com/repository/img/image.jpg)
```
By default, images should be in the folder /img/ and labeled according to the file in which they are first used. If the file is R50-plotting.md , the image should be callded R50-ScatterPlot.png.



### Linking Videos 

```
<a href="http://www.youtube.com/watch?v=q1RD5ECsSB0" target="_blank">
![Video](http://img.youtube.com/vi/q1RD5ECsSB0/0.jpg)<br/ >
Video demonstrating multiple linear regresssion in R
</a>
```

# Developers / Admins

Shifting changes from md to the page is easy, just merge the main branch in the gh-pages branch. 

If you want to change css and other elements in the gh-pages branch, you need to install a local Jekyll version, you can't really debug problems by commiting to GitHub and see how things change. See [here](https://help.github.com/articles/using-jekyll-with-pages/#installing-jekyll) for a tutorial on installing Jekyll

Create site from terminal with bundle exec jekyll serve



