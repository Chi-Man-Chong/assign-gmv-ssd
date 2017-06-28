# Stop Sign Detection in Google Street View Images Using the Haar Cascade Classifier

Richard Wen  
rwen@ryerson.ca  
June 27, 2017  
Assignment for Geospatial Modelling and Visualization Course  
Instructed by Dr. Wai Yeung Yan  
  
- [PDF](https://github.com/rrwen/assign-gmv-ssd/blob/master/paper/pdf/index.pdf)

Paper report in LaTeX on stop sign detection experiment in Google Street View Images.

## Folders

* **_img**: Stores images used in the paper
* **log**: LaTeX generated logs and files
* **pdf**: The compiled pdf generated from index.tex using LaTeX

## Developer Notes

1. Install [TeX Live](https://www.tug.org/texlive/acquire-netinstall.html) or [Miktex](https://miktex.org/download)
2. Add bin paths to system or environmental paths 
3. Generate **pdf/index.pdf**

```
latex index.tex -output-directory=log -interaction=nonstopmode
bibtex log/index.aux
latex index.tex -output-directory=log -interaction=nonstopmode
pdflatex index.tex -output-directory=pdf -aux-directory=log -interaction=nonstopmode
```

Regenerating the PDF (if references or citations have not changed):

```
pdflatex index.tex -output-directory=pdf -aux-directory=log -interaction=nonstopmode
```