# Site Blog Posts - repository
## About
* this repository is to house the daily posts and other blog posts added to our website

---

## Plans/Pathway
* taken from the notes made in the`corbeau217.github.io` repository
### Milestone 0 - init
- [x] blog post repostory repo created
- [x] planned out the milestones
### Milestone 1 - make it exist
- [x] direct port of current structure with no changes to functionality
    - [x] daily post files now separated to their own repository
    - [x] stylesheet left in parent repo
- [x] add as submodule
    - [x] update paths to take post files from submodule
- [x] verify working
### Milestone 2 - baby steps
- [x] update image paths to be using the submodule location
- [x] analyse if current structure can have new post generation be automated
- [x] determine next steps regarding `.md` and `.sh` files
- [x] confirm if we can still use `XMLHttpRequest`
### Milestone 3 - automation
- [ ] `.md` support
    - [ ] create script file for conversion of `.md` to appropriate html code
### Milestone 4 - automated new files
- [ ] `.sh` to generate the list of posts
    - [ ] generates file header
    - [ ] searches folders to get paths
    - [ ] uses placeholder metadata
- [ ] look in to having header at the start of `.md` files to hold information
    - [ ] can our `.sh` file read this and include it in our list of posts?
### Milestone 5 - "more"
- [ ] small number loaded from most recent, action is taken to request more
    - [ ] button to load X more
    - [ ] investigate infinite scrolling

---

## post extensions

### `.html` / themed posts
* currently converted in to cards on the site when it's up and viewable
* these are themed daily posts based on the day they were made
* the format was starting to spiral in to an expectation for success which chased away the original intent of the posts

### `.md` / un-themed posts
* not currently (20250522) converted in to cards for the site
* used for exploring ideas separate from a theme, without cluttering up documentation of other projects
* these may or may not be acted apon in the future, and are mostly intended to get the brain worm somewhere to exist without burying it out of sight
* usually reserved for open source projects and ideas which arent directly dependent on another project
