# Student Guide

# insert the command to convert adoc to word

```
INPUT_ADOC=my_input_file.adoc
asciidoctor --backend docbook --out-file - $INPUT_ADOC| \
pandoc --from docbook --to docx --output $INPUT_ADOC.docx
```
> Src: https://rmoff.net/2020/04/16/converting-from-asciidoc-to-google-docs-and-ms-word/


# command to convert word to adoc
```
pandoc X.docx -f docx -t asciidoc --wrap=none --markdown-headings=atx --extract-media=extracted-media -o src/output.adoc
```
# command to convert adoc to html
```
asciidoctor X.adoc
```
