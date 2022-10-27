# Hello world


adoc -> (((( md ->  html ))))

adoc -> .docx 
adoc -> .pdf
adoc -> .mobi/ .epub 
adoc -> html


Inside the email
Hey, this is the solution. See url (suss-vli.github.io/0/s/faq/first.html#second)

1. Thus the solution will be to provide an easy way for them to search teh solution. Or easy way for US to search for one and provide the link. 
2. There is a greater need to semantic version control. e.g v4.0.1
3. Provide a link to github repo for them to search it.

# [Second solution](#second)

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