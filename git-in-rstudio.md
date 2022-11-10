# Git in RStudio
> ## Overview
> RStudio and version controls
> - Git
> - Subversion
>
> For this lesson we will focus on git
{: .objectives}  

### RStudio projects (required for version control):
- RStudio projects make it straightforward to divide your work into multiple contexts, each with their own working directory, workspace, history, and source documents.

## Step-by-Step
1. Fork the `rr-version-control-demo` repository.
1. Clone your forked repository to obtain a local copy of the files into an RStudio project.
1. Edit a file in this repository/project.
1. Stage your changes to be committed.
1. View the diff, and commit your changes, with a commit message.
1. Push your changes to your own fork of the the `rr-version-control-demo` GitHub repository.

### Step 1: Fork
- Go to the [`rr-version-control-demo`](https://github.com/Reproducible-Science-Curriculum/rr-version-control-demo).
- Click on Fork (on the top right corner).

_Now you have a copy of_ `rr-version-control-demo` _repository in your account, woohoo!_

#### Aside - where am I?
**How can I tell if I am looking at my fork or the original repository?**
- Look at the URL
- Look at the name of the repo on the upper left corner, for your fork it will say:

`[your-github-name]/rr-version-control-demo`

`forked from Reproducible-Science-Curriculum/rr-version-control-demo`

### Step 2: Clone
- In RStudio, go to File, and then New Project
- Click on Version Control: Checkout a project from a version control repository
- Click on Git: Clone a project from a repository
- Fill in the info:
  - URL: use HTTPS address
  - Create as a subdirectory of: Browse to where you would like to create this folder

### Step 3: Edit
- Open the file called gdp-life-expectancy.Rmd and knit.
- Change the analysis_year to another year for which we have data (1952, 1957, 1962, 1967, 1972, 1977, 1982, 1987, 1992, 1997, 2002, 2007), and `knit` again. Examine the output for changes.

### Step 4: Stage
- Go to the Git pane in RStudio.
- Stage the changes for `gdp-life-expectancy.Rmd` and `gdp-life-expectancy.html` by checking the boxes next to then, and hit `Commit`.

_Don't worry about the other files that appear in this pane, we'll get to them in a bit._

### Step 5: Commit
- In the pop-up window view the diff for the `.Rmd` file. You can view it for the HTML file as well if you like.
- Enter an **informative** commit message, like "Changed analysis year to X", and hit Commit.

### Step 6: Push
**push**: When using git push always means pushing commits from your local respository (your computer) to a remote repository (Github).
- Now push your changes to GitHub by hitting `Push`.
- Enter login information as needed.
