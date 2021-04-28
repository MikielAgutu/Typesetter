# Typeset ![build](https://github.com/MikielAgutu/Typeset/actions/workflows/dotnet.yml/badge.svg)

Typeset - Convert markdown to print ready PDFs

## Example

```
typeset -i C:\chatper-1.md C:\chapter-2.md -o C:\myBook.pdf
```

## How to use

- Checkout this repo
- Run `./build/Build-TypesetCommandline.ps1`
- `cd` into `output/typeset-cli-windows` to run

You can then copy `typeset-cli-windows` to a convenient place on your machine, then set `PATH` to point to it.

Only supports Windows at the moment.

## Documentation

```
  --fontFamily            (Default: Arial) Font family to use for all text in the document

  --pageSize              (Default: A4) Page size of the document

  --pageMargin            (Default: 70pt 60pt 70pt) Margin around the text

  --lineHeight            (Default: 200%) Height of each line of text

  --fontSize              (Default: 14pt) Font size for main text of document

  -i, --inputFilePaths    Required. Markdown files to create into a document

  -o, --outputFilepath    Required. Where to output the document PDF

  --title                 (Default: ) Title of the document

  --printPageNumbers      (Default: false) Whether to print page numbers

  --printPageMarginals    (Default: false) Whether to print page marginals

  --help                  Display this help screen.

  --version               Display version information.
```
