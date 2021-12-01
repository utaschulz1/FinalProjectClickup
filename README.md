# FinalProjectClickup
This is the final project of the course about software documentation with [Jordan Stanchev](https://github.com/JordanStanchev/Getting-Started-as-User-Assistance-Developer). 

## Topic
I chose to document Clickup, a productivity app, in particular the form building function.

## Target audience form builder feature
My target audience are users like me: Those users would use Clickup for business and/or private life to organize time and resources and plan goals and projects on a more or less granular level. On their journey learning about Clickups possibilities users would integrate more and more processes into there Clickup workspace, like accounting or vendor management. My users are computer literates and take an effort to understand workflows and automations. Those users have no coding skills and do not speak developers' lingo.

## Target audience API endpoints for building testimonials on website
web developer, Clickup users with low-code experience

## Feature documentation
The form builder feature in Clickup creates a form, called a form view, that can be shared and embedded. If the form is submitted a task is created tht contains the specified fields and data.
### Topic formats
* concepts topic headings have the format: About concept
* tasks topic headings have the format: How to create a task
* before the first step, there is a list of prerequisites. If there are non, it says that there are non or it states the starting point
* steps have the format: STEP # Opening the first window
* results have the format of a blockquote 
>I am a result
* UI elements have the format of a codeblock: `UI element`
* names can be formatted as _italic_
* checkboxes are _enabled_, not checked, not activated
* reference topics preferably have the format: list or table

## API documentation
Endpoints for getting data from tasks depending on status will be addressed. As an example, the form data from the earlier built form will be queried and used to build a testimonial on the website.

The API documentation was created on Swagger and pushed to the docs in this project.
The example code for the API documentation is in this repo.

The documentation of the form builder feature and API live on the Wiki page of this project.
