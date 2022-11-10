# Introduction to Version Control

## Recording the history of your projects
### What is version control?
Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

## Question?
How do you record the history of your projects?

### Bad - Run on file names
![Final.doc comic](/carpentries-rr-vc/assets/img/final_PhD.png)

[PhD Comics](http://www.phdcomics.com)

### Good - Informatively named files
```
   2013-10-14_manuscriptFish.doc
   2013-10-30_manuscriptFish.doc
   2013-11-05_manusctiptFish_intitialRyanEdits.doc
   2013-11-10_manuscriptFish.doc
   2013-11-11_manuscriptFish.doc
   2013-11-15_manuscriptFish.doc
   2013-11-30_manuscriptFish.doc
   2013-12-01_manuscriptFish.doc
   2013-12-02_manuscriptFish_PNASsubmitted.doc
   2014-01-03_manuscriptFish_PLOSsubmitted.doc
   2014-02-15_manuscriptFish_PLOSrevision.doc
   2014-03-14_manuscriptFish_PLOSpublished.doc
```

## Better - Saving everything together at once

Everytime you make a save, you zip the entire directory that your project files are in and save it with a date.

## Best - Version Control

![Example of good version control](/carpentries-rr-vc/assets/img/ropensci_RNeXML.png)

[Code for `RNeXML` `R` package, plus RNeXML publication in `RMarkdown`](https://github.com/ropensci/RNeXML)

## How does a version control system work?
- Version control systems start with a base version of the document and then save just the changes you made at each step of the way.
- You can think of it as a tape: if you rewind the tape and start at the base document, then you can play back each change and end up with your latest version.

![Visual representation of changes made to a file](/carpentries-rr-vc/assets/img/software_carpentry.png)

[Software Carpentry](https://software-carpentry.org/)

- You can then think about "playing back" different sets of changes onto the base document and getting different versions of the document.

![Visual representation of merging changes](/carpentries-rr-vc/assets/img/software_carpentry_2.png)

[Software Carpentry](https://software-carpentry.org/)

## Why use Git and GitHub

### Why use Git?
- Makes you fearless
- Easy to set up
- Allows you to take a snapshot of every stage of your project history
- Takes up minimal space
- Creates a easy navigable map to the history of all changes made

### Features of using a Hosting Service Like GitHub
- Backup of your project
- No need for a server: easy to set up
- GitHub's strong community: your colleagues are probably already there
- Provides tools to help enhance collaboration
- A common location to share off your work

### Example
![ropensci example as hosting service](/carpentries-rr-vc/assets/img/ropensci_RNeXML_2.png)

[Code for `RNeXML` `R` package, plus RNeXML publication in `RMarkdown`](https://github.com/ropensci/RNeXML)
