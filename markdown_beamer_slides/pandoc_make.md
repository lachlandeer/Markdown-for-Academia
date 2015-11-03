

## set directory 
On a windows machine:

cd "C:\where\your\file\is"

### with a custom theme via preamble.tex and bibliograpgy -> the one you want to run
pandoc -t beamer -H preamble.tex slides.md --filter pandoc-citeproc --slide-level 2 -o slides.pdf

