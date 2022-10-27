# Hello world


adoc -> (((( md ->  html ))))

adoc -> .docx 
adoc -> .pdf
adoc -> .mobi/ .epub 
adoc -> html


# Second solution

1. If automation is not done properly, then it's going to be hard. 
# regarding the adoc -> md conversion

1. We will store the `.adoc` in seperate repo
2. We will clone these repo ^ into our localhost
3. We will run some commands/script e.g. `python3 setup.py`
In those scripts, it will contain `mv student-guide/faq/* suss-vli.github.io/faq/*`
4. Once #3 is done, we will have the source at suss-vli.github.io ready to become HTML. 
# For instance
mv student-guide/faq/* suss-vli.github.io/s/faq/*
mv instructor-guide/faq/* suss-vli.github.io/i/faq/*
mv admin-guide/faq/* suss-vli.github.io/a/faq/*