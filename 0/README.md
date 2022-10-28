Visit [student-guide faq](https://suss-vli.github.io/0/student/guide/faq)

# Version 0 of the guides

This is the documentation for `students`

# Pull content from each submodule

At its respective directory, simply run `git pull` to pull the content into its respective directory

e.g. To stay up to date with instructor-guide content, run the following command

```
cd 0/instructor
git pull
```
# To add future submodule

Run `git submodule add <github-url> <path-to-clone-to>`

e.g To add a repo to the path `0/instructor`
```
git submodule add https://github.com/suss-vli/instructor-guide 0/instructor
```

# Naming convention

Besides the default page `index.md` of every directory, other .md should use a `meaningful`, `small cap` and use hyphen `-` to join the name.

For instance, the page on github classroom should probably have a `github-classroom.md` and contain every information about github classroom. 

If the topic is too big, then i will propose having a directory called `github-classroom` and have other pages like `how-to-setup-github-classroom.md` or `how-to-authenticate-with-github.md` in that directory. Consequently, the url will be updated to have `suss-vli.github.io/0/student/github-classrom/how-to-setup-github-classroom.html` etc. 

A second example, for `getting-started.md`, it should contain `prerequisites` and `quick-start` as content and subtitle. Naturally, subtitle will become anchor link. 
