# README.md

This is my personal resume. Feel free to look around or use it as template for your own. It's written in [Markdown](https://en.wikipedia.org/wiki/Markdown) and to generate a .pdf file from it I use [pandoc](https://pandoc.org/).

## How to generate a .pdf:

First install pandoc. You'll also need [weasyprint](https://weasyprint.org/). On Ubuntu-like distributions run:

```
$ sudo apt install pandoc weasyprint
```

Then to generate the .pdf run:

```
$ pandoc -t html --pdf-engine=weasyprint --css resume-stylesheet.css resume-en.md -o resume-en.pdf
```