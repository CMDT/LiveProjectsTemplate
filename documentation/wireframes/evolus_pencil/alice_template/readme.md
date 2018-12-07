# User Story Example: Alice Creates a Template
## Background

This is a user story taken from the [Make Progress brief](./brief_make_progress.pdf).

### Alice

Alice is a teacher. She uses the Make Progress app to understand how her students' confidence changes as they go through her course. The course is on software engineering and there are lots of aspects of it which she wants to keep track of. For example:

* Personal: Time Management and organisation
* Personal: Working alone
* Persona: Working as part of a team
* Technical: interpretation of instructions
* Technical: writing user stories
* Technical: feature design
* Technical: component design
* Technical: planning

Alice, as a teacher will be  creating template 'wheel' charts, for her students to fill in. Each wheel has attributes which map directly to the student's confidence in a course aspect. When she creates a wheel, she will save it, and distribute it to her class, later.

At the end of each teaching session, she asks her class to fill in their wheel for today. Each student considers their confidence in each of the aspects, and prompted by the app, assigns meaningful number to each one. 

At the end of the course, each student has a wheel filled with their own personal evaluation of their confidence. Alice asks the students to email them to her, for evaluation.

### Why are we doing this?

By setting a **single goal** for the character to get to and working out how the app will make it easy for them to accomplish this, we can write a user story.

A user story is the first stage of imagining the use of the app; it describes how the character uses the app to get to their goal.

The user story concerns itself only with the 'happy' path to the goal. That is, describing the minimal steps which the app will provide to achieve it.

A user story is written with the character and the app in mind, and commonly you would start with a pencil on paper.

Later, you would use a prototyping tool like [Evolus Pencil](http://pencil.evolus.vn/) to help you flesh-out the concept. As you make it more detailed, the look and feel of the app starts to come together. Soon, it is good enough to extract features.

## User Story

Here's the example user story; Alice Creates A Template. The Evolus Pencil illustration is [here](./UserStoryIllustrations/AliceCreatesATemplate.epgz). You can run the html demo locally [here](./UserStoryIllustrations/export/index.html).

Alice wants to create a template to send to her students. They will fill it in, and send it back to her via email.

1. Alice opens the app at the 'home' screen. 
2. She sees a hamburger menu and taps on it. 
3. She selects the item 'templates'. 
4. The home page is replaced by a new page.
5. The new page informs Alice that she doesn't have any templates, and that she can create one. It shows her a button to press to do this.
6. Alice presses the button. 
7. The first page of a wizard appears. It prompts Alice to enter a name for the template.
8. The next page prompts Alice for the maxmimum and minimum of all attributes in the template.
9. The next page informs that this template has no attributes, and that she should add some. It shows her a button to press to do this.
10. Alice presses the button.
11. A new page is shown. It prompts alice to enter a name and a description for the attribute. Alice finds she can only enter a limited number of characters for the name, but she can enter as many as she needs for the description.
12. When Alice has finished, she presses a button to indicate this. The page is dismissed.
13. A new page allows Alice to select a representative colour for the attribute.
14. When she is finshed, she can press another button. The page is dismissed. 
15. Alice can now see the previous page, which has her new attribute listed.
16. Alice uses this page in the same way, to add several more attributes. 
17. Once the list has all the attributes she needs, Alice presses a button to accept them.
18. The template is complete. Alice is returned to the templates page, which lists her new template by its name.

Wireframe shots can illustrate the user story.
Wireframe prototypes with notes can fully describe behaviour, and are the first step to describing app features.

**Remember**

Keep interactive wireframe demos **small**. One per feature. Only model the 'happy' path (the one which gives you the preferred result)

User stories can be gathered together ina meaningful flow, by using a mind-mapping tool, such as [MindMup](https://drive.mindmup.com/)

## Tools 

* [Evolus Pencil](http://pencil.evolus.vn/)
* [Evolus Pencil Pretotype Plugin](https://rudylattae.github.io/evoluspencil-pretotype-template/)


Using Evolus Pencil, you can quickly create wireframes with behaviour to illustrate each feature or user story. 

Using the Pretotype plugin, you can export the wireframes and behaviour to html. 

If you export to the /docs folder in this project, you can deploy the wireframes to their own GitHub pages site. Our example wireframe is published [here](https://cmdt.github.io/LiveProjectsTemplate/#/page/start).

You can try [Axure RP](https://www.axure.com/), because it's available on the campus computers. You can compare and contrast the two. Take a look at the examples and their exports in this folder.







