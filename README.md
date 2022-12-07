Version: v0.1.0.alpha1

This is the homepage of project VLI of SUSS. It also contains the submodules guides.

We use open-source tools like `adoc`, `jekyll`, `markdown`, `codespell` and others. 


# Regarding Guides

## Using submodules for guides

The first version of the guide is found at `0/`

We are using `git submodules` to clone its source code into this github pages. Thus, the source code `suss-vli/student-guide`, instructor-guide is at `suss-vli/instructor-guide` and `suss-vli/admin-guide`

## Write where? Here or its respective submodules. 

You should be writing at the repo of its respective submodules. For instance, if you want to update student-guide, you should go to [`student-guide`](https://github.com/suss-vli/student-guide) repo and push changes there. We will pull the changes at this repo in the future. 


## To get the latest update from submodules 

Go to the respective directory, run `git pull` to pull the content. 
e.g. `cd 0/instructor; git pull`

# TODO

- [ ] Add a yellow highlight to each anchor link of each guide. 
- [x] Generate a frontpage for VLI
- [x] make sure you have sticker footer
- [x] Introduce semantic versions e.g v1.0.0 to track changes
- [x] automatically calculate the final year at the bottom 
- Regarding the student guide for interactive lab guide by VLI + Github Classroom
- [ ] Bigger Gif?
- [ ] Gif for two platforms: window and mac. We are only supporting generally window and mac
- [ ] Test the workflow
- [ ] Setup CI/CD such that the pdf, html and other versions are auto-generated via each commit
- [ ] Jane suggested using video instead of Gif
- Use Git for step by step animated image
- Use mp4 for an overall start to end demostration
Idea: To have an interactive guide that encourage self-help
- Consider using https://github.com/ines/termynal to animate the temrinal for the lab author's guide
- Use this for the frontpage https://startbootstrap.com/previews/business-frontpage

This may be the best meme to [explain](https://twitter.com/PR0GRAMMERHUM0R/status/1561247203443752960) git to anyone

## for FAQ

- [ ] highlighting ability like stackoverflow (click link to see yellow fading highlight effect): https://stackoverflow.com/a/74258030/388280
- [ ] May need this type of knowledge-based style: https://github.com/TeaGuns/odin - odin is open-source
- [ ] maybe we can surround commands in such boxes https://kevquirk.com/how-to-create-a-simple-html-css-notice-box/ - submitter already has this

# Regarding Frontpage
- [] add an animation to the header. certain page load should remain static. Subtitle should experience animation. Use https://www.vantajs.com
- [] change the call-to-action button to respond correctly to mobile view
- [] add a page to call for interns & software engineers (devops, full-stack & data science) & craftmen and craftwomen for VLI project
- [] add these to the website to get time https://time.is/widgets
