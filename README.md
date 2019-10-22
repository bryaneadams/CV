# Curriculum Vitae in R, why not!?!?!

I have been told to always keep my CV updated, but it is a pain to format it in Latex or Word.  `RMarkdown` is easy to use, much easier than Latex, and easier to format, much easier than word.  I am also able to use the same `RMarkdown` file on [my blog](https://bryanadams.netlify.com/about/).  

## What you need.

You need the following:

1. A Latex compiler:  [MikTex](https://miktex.org/) is what I use.
2. R

## What you need to change.

Beside writing your own items, the only thing you need to change is in the `YMAL`.  Under the `YMAL` you will see:

```r
output:
  pdf_document:
    latex_engine: xelatex
    template: C:\Users\Bryan.Adams\Desktop\GitHub\CV\svm-latex-cv.tex

```
After `template:` you need to change where you have the `svm-latex-cv.tex` file saved.
    

