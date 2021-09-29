# README

<!-- REMEMBER: 
You can preview a formatted version of this README.md document by clicking the 'Preview' button in the RStudio toolbar.
-->

## Preparation

- Reflect on your interests in language and linguistics
- Review the concepts on identifying a research problem and developing a research statement in [TAD Chapter 4 "Framing"](https://lin380.github.io/coursebook/framing-research.html)
- Refine your project statements from Project Orientation #5.
- Review the steps for working with RStudio, Git, and GitHub in [Recipe #5](https://lin380.github.io/tadr/articles/recipe_5.html) and Lab #5. 

## Objectives

- Continue to refine your project statements
- Add you project statements to your project template
- Apply the edit, add, commit, push workflow to update your GitHub page
- Continue to apply your growing knowledge of R Markdown

## Instructions

### Setup

1. Open your research project (`project_<your_last_name>`) on RStudio Cloud. 
2. Open the `index.Rmd` file in the `analysis/` directory. 

### Project

1. Add your (current) project statements to this `index.Rmd` file under the appropriate headings.


*Note: The statements and articles you include in this project orientation should not be seen as a set-in-stone commitment to a research project topic/question/etc. The statements will likely change in the coming weeks, but it is important to make a concerted effort to develop a research blueprint at this point if nothing else but to give you a point of reference. We will workshop the ideas that surface from the work on this project orientation step and discuss collective and individual questions to continue to develop and hone our projects so that they show the most promise for being viable.*


2. Source the `_pipeline.R` file. Either through: 
  - opening the `_pipeline.R` file and clicking the 'Source' button.
  - or, in the R Console runninng `source("_pipeline.R")`

### Update GitHub

1. Now run the Git commands in the Terminal to add, commit, and push your updates to your GitHub repository/ website. 

**Remember:** your PAT has probably expired (it only lasts 12 hours in RStudio Cloud) so you will need to run `gitcreds::gitcreds_set()` in the R Console and paste in your PAT before you run `git push` (otherwise you will get cryptic error). 

- `git status`
- `git add -A`
- `git commit -m '<briefly describe what you've done>'`
- `git push`

## Submission

1. Navigate to your GitHub website (where the web page shows) and copy the link to the main page where you have added your changes. 
3. Go to the Canvas submission page for "Project implementation #1" and paste this URL link into the 'website url' submission field. In the 'Text Entry' field add your self-assessment comments.

**IMPORTANT NOTE:**

We will be using GitHub to post our work from here on out. In addition to saving our project work and hosting a website for our projects, GitHub also has a robust set of features for commenting and collaborating on code. We will use these features to receive and ask for feedback on our code and ideas.





