# pdfmake
some simple tools for creation of PDF from markdown
## Need to Install

_You need at least go 1.21 to make this work._

```bash
brew install wkhtmltopdf

go install github.com/russross/blackfriday-tool@latest
```

then run `./pdfmake ZCW-BCI-DATA-Q1-2024.md` (or whatever file you want to make PDF)

Use `-x` to get `confidential and proprietary` on the footer/header.

COPYRIGHT is set to 2024 in footer.html(!)
