# Welcome to the BOP Wiki!

This repo hosts the BOP Wiki. The wiki is built with Hugo and uses the Docsy theme.

## Repo Layout
There are 2 primary branches in this repo: `main` and `gh-pages`.
`gh-pages` is updated automatically by TravisCI whenever a change is pushed to `main`. It can not be updated manually.

## Writing Content
Everyone is welcome to write content! And no web dev experience encessary, as all content is written in Markdown! 

### Content Creation Process
If you are making edits to existing pages/sections, you can simply submit a PR to `main`. However, if you are adding a new page(s) or section(s), then please create a branch for your work and submit a MR.

All content changes should be made within [`content/en`](https://github.ibm.com/BoxBoat-OpenShift-Practice/bop-wiki/tree/main/content/en). There are currently 3 types of content: 
1. Docs
2. Blogs
3. Community

All wiki material should be placed in the appropriate section within Docs. If you aren't sure which section in Docs your content fits, please reach out to the wiki admins for guidance. 

The best practice for content creation is to create a folder for your new section, with the content written in a new `_index.md` file within the dir. All images can then be placed within the associated dir and referenced from there. And don't forget your Front Matter!

## Build Locally
- Install Dependencies
- `hugo server`

