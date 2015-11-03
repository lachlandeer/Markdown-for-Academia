---
author:
- Joe Bloggs
- Helmut Schmidt
subtitle: With Subtitle
title: An Example Title
titlepage-note: |
  This is a the note that goes on the title page. This talk is to be 
  given at Doing DH.
institute: Not included for now
bibliography: refs.bib
csl: chicago.csl
...



## Slide Heading

* Here is a bullet
    * And a sub-bullet

1. Here is a numbered List

\note{
~
}

## Slide with text and footnote

An equation system drawn from another file... using a "tex" code

\input{./equations/iv.tex}

## An interesting Title about a picture

![image caption](./figure/sample-image.jpg "beautiful cat")

## A Latex Regression Table
\input{./table/table1_reg_on_indicators.tex}


## Some References
The table on the last slide was from a replication study by @Albouy12.

Can also references like this [@AcemogluJohnsonRobinson01]

## Code example
Here is some Ruby code for fun
``` {.ruby}
puts "Hello world."
def my_awesome_variable
  puts "My awesome variable"
end
```

## Reference list
Reference list automatically added by pandoc
