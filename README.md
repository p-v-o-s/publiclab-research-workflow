publiclab-research-workflow
===========================

### Overview 

This describes a way of both on-ramping folks who are used to writing articles for traditional scientific publications into the publiclab.org ecosystem; it also describes an option for research note creation that will make writing and maintaining complex research notes much easier for any researcher in the Public Lab community, without interfering with the current work flow that has developed.

## Basic idea 

- Add the code / button / feature necessary on a publiclab.org research note 'edit' page to allow for that research note to 'link to / import' a markdown file located external to publiclab.org -- in, e.g., a github repository.  
- This might a one-time import of the markdown text contained in that external file; or this might involve the publiclab.org research note always loading the lastest version of that external markdown file, every time the research note is served on publiclab.org.
- This would allow for users to version control their research notes externally, which would likely appeal to folks who are concerned with control over their own data, and would make 'publishing' on publiclab.org an easier proposition
- This might lead to a 'write once, publish many places' approach, so that people wouldn't need to re-write / edit all of their research when reaching different audiences.  E.g. they could write a research note, and store it in their github or other repo; then that note could be published a) on their own blog, to allow for comments from their personal community, reach that audience b) on publiclab.org, to benefit from the PL community / tag system / comment structure and c) in another online journal.
- For more complex research notes, having the option for an external editor, and local storage, makes things much easier / more stable.  Can edit notes locally, off-line, using text editor workflow of one's choosing; can organize files locally; then publiclab.org is used to display results, and provides curation 'comment' and 'tag' infrastructure around material.  I.e.:  publiclab.org is the overarching community discussion around that published material. 
- Could be seamlessly integrated with 'shorter' reserach notes, where note creation takes place completely online via web entry form on publiclab.org
- Takes some of burden off storage of images and data on publiclab.org, as we begin to accumulate larger datasets re: time series data, images, etc


## How to incorporate
- Allow for 'link to github markdown directory' button, which points at github repo, and intelligently imports the relevant files from the github repo?  E.g. it would import index.md, and then parse the relative URL structure in order to import any files in an '/images' or '/data' directory in that github repo
- Perhaps there's the option to 'always import data; don't store on publiclab.org' as well as a 'store data on publiclab.org; update only if there is a more recent version in external repo' option.  This would allow users to decide whether they wanted to control the data externally (re: privacy and etc).  
- Render LaTeX, so that equations can be incorporated.  This is a key, needed feature.

## Credits

- This is an idea that came up in discussion with Jeff Walker, whose several recent writeups in markdown are stored in github repos.  He found that his best workflow seemed to be to maintain the markdown files he'd written, as well as the images files they referred to, in his own github repo.  When it came time to publish on publiclab.org, we tried copy-pasting his markdown, and uploading all of the image files individually; but this quickly became a bit painful.  It occurred to us that an option for simply linking a publiclab.org research note to an external repo would be a great feature. 
