# FinalProjectClickup
This is the final project of the course about software documentation with [Jordan Stanchev](https://github.com/JordanStanchev/Getting-Started-as-User-Assistance-Developer). 

## Topic
I chose to document [Clickup](Clickup.com), a productivity app, in particular the [form building function](https://github.com/utaschulz1/FinalProjectClickup/wiki/2-Clickup--views#form-view).

## Target audience form builder feature
My target audience are users like me: Those users would use Clickup for business and/or private life to organize time and resources and plan goals and projects on a more or less granular level. On their journey learning about Clickups possibilities users would integrate more and more processes into there Clickup workspace, like accounting or vendor management. My users are computer literates and take an effort to understand workflows and automations. Those users have no coding skills and do not speak developers' lingo.

## Target audience API endpoints for building testimonials on website
web developer, Clickup users with low-code experience

## Feature documentation
The form builder feature in Clickup creates a form, called a form view, that can be shared and embedded. If the form is submitted, a task is created that contains the specified fields and data.
### Topic formats
* concepts topic headings have the format: About [Clickup Tasks](https://github.com/utaschulz1/FinalProjectClickup/wiki/1-Getting-startet-with-Clickup#clickup-tasks)
* tasks topic headings have the format: [How to create a form](https://github.com/utaschulz1/FinalProjectClickup/wiki/2-Clickup--views#how-to-create-a-form)
* before the first step, there is a list of prerequisites. If there are non, it says that there are non or it states the starting point
* steps have the format: STEP # Opening the first window
* results have the format of a blockquote 
>I am a result
* UI elements have the format of a codeblock: `UI element`
* names can be formatted as _italic_
* checkboxes are _enabled_, not checked, not activated
* [reference topics](https://github.com/utaschulz1/FinalProjectClickup/wiki/Clickup-API---Get-and-Post-field-data-from-tasks#api-supported-field-types-of-custom-fields) preferably have the format: list or table

## API documentation
2 Get methods and 1 Post method will be described using Swagger UI. One Get method is to call a complete Clickup task, the other Get method calls all accessible custom fields in a list and the Post method can set custom fields in a Clickup task.

The [yaml file](https://github.com/utaschulz1/FinalProjectClickup/blob/main/FromSwagger-FinalProjectClickupAPI-1.0.0-resolved.yaml) and [html file](https://github.com/utaschulz1/FinalProjectClickup/blob/main/FromSwagger_ClickupAPI.html) of the documentation of thos 3 API endpoints are in this repo and on [Swagger](https://app.swaggerhub.com/apis/UMTranslation/FinalProjectClickupAPI/1.0.0)

The documentation of the [form builder feature](https://github.com/utaschulz1/FinalProjectClickup/wiki/2-Clickup--views#form-view) and [API](https://github.com/utaschulz1/FinalProjectClickup/wiki/Clickup-API---Get-and-Post-field-data-from-tasks) live on the Wiki page of this project.
