---
title: Your title here
abstract: Your abstract here
date: \today
author:
    - Vlad


###
### Bibliography settings
###
bibliography:
    - ./zotero.bib
csl: ./styles/ieee_with_url.csl
link-citations: true


###
### Formatting settings
###
documentclass: article
fontsize: 12pt
geometry: "left=3cm,right=3cm,top=2cm,bottom=2cm"
header-includes:
    - \usepackage{times}
urlcolor: blue


###
### Markdown Preview Enhanced package settings
###
output:
    pdf_document:
        toc: false
        number_sections: true
---

# Introduction

...

# Related work

@example_book

# Conslusion

@example_link