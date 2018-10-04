# LiveProjectsTemplate
This is a template, which lays out a structure for a main project. It can be used by any team working on an MMU LiveProject.

**NOTE**: Your live projects are PUBLIC, on both GitHub and Trello meaning anyone can see them. 

**To keep you and your client safe**, here are some ground rules:

* **NO authentication data:** 
  * usernames, passwords
  * shared secrets
  * tokens
* **NO real names** 
  * no personally attributable data of any sort

**Your repo will turn up on public searches.** Likely initiated by people just like yourself; desperate for information. Please help them!

* Keep your code clear and concise
* Constructive comments only
* Give a helpful overview or how-to in a readme.md

**Use a gitignore file:** You'll find there is a need only to store a tiny fraction of your source files in a repo. These files depend on the sort of product you are building, and the frameworks you are using. More information (and a selection of gitignore files for common frameworks!) can be found [here](https://github.com/github/gitignore). 

**Make sure your product's version is visible to the user at all times:** any problems, you can ask them to raise a GitHub issue, stating the version of the product. 

**This file is your front page:** Replace the above with text which will help the people who use your project, or may build on it next. Link to your brief, your design, how to build and how to use your product.

## Contents

###  Folders

#### [docs](https://cmdt.github.io/LiveProjectsTemplate/#/page/start)

Holds live wireframes for the project. 

(Can also be used to hold the published code, if deploying a single project to GitHub Pages).

#### [documentation](./documentation/readme.md)

Holds documentation for the project. See folder for details

#### [code](./code/readme.md)

Optionally, the source code for the project goes here. If the project has many deployable components (servers / apps), each one has it's own [subproject](https://github.com/CMDT/LiveProjectsSubProject).

#### [investigations](./investigations/readme.md)

Example code, and helpful snippets

### Sub Projects

Link to your sub-projects here. Clone the [sub-project repo](https://github.com/CMDT/LiveProjectsSubProject) for each one.

### Trello

Link to your Trello boards here:

* Overview
* Discussions
* User Stories
* Investigations
* Implementations
* Features
  * sub-feature (if needed)
  * ...
* Design
  * component (if needed)
  * ...
* Tasks
* Plan

