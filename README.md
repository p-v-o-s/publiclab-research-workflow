publiclab-research-workflow
===========================

publiclab-research-workflow
===========================

### Overview 

This describes a way of both on-ramping folks who are used to writing articles for traditional scientific publications into the publiclab.org ecosystem; it also describes an option for research note creation that will make writing and maintaining complex research notes much easier for any researcher in the Public Lab community, without interfering with the current work flow that has developed.

## Basic idea 

- Allow for research notes to 'import' markdown files from a github repository or other external source.  This might a one-time import; or this might be a link in the research note that always checks for the external file, and loads it in.
- This would allow for users to version control their research notes externally, which would likely appeal to folks who are concerned with control over their own data, and would make 'publishing' on publiclab.org an easier proposition
- This might lead to a 'write once, publish many places' approach, so that people wouldn't need to re-write / edit all of their research when reaching different audiences (e.g. they could write material that would go on their own personal blog and publiclab.org) 
- For more complex research notes, having the option for an external editor, and local storage, makes things much easier / more stable.  Can edit notes locally, off-line, using text editor workflow of one's choosing; can organize files locally; then publiclab.org is used to display results, and provides curation 'comment' and 'tag' infrastructure around material.  I.e.:  publiclab.org is the overarching community discussion around that published material. 
- Could be seamlessly integrated with 'shorter' reserach notes, where note creation takes place completely online via web entry form on publiclab.org
- Takes some of burden off storage of images and data on publiclab.org, as we begin to accumulate larger datasets re: time series data, images, etc


## How to incorporate
- Allow for 'link to github markdown directory' button, which points at github repo, and intelligently imports the relevant files from the github repo?  E.g. it would import index.md, and then parse the relative URL structure in order to import any files in an '/images' or '/data' directory in that github repo
- Perhaps there's the option to 'always import data; don't store on publiclab.org' as well as a 'store data on publiclab.org; update only if there is a more recent version in external repo' option.  This would allow users to decide whether they wanted to control the data externally (re: privacy and etc).  
- Render LaTeX, so that equations can be incorporated.  This is a key, needed feature.
