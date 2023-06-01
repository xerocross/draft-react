# Draft-React (2019)

This is a tiny React widget for drafting plain text that lets you commit (or save) your changes in a very simple way and then browse backward and forward among your committed changes. I like to think of it as a simple but powerfully improved undo-redo system, inspired by Git (but obviously much simpler). I imagine the user as someone fretting over choosing exactly the right wording for an email to his boss or something like that.

### No Backend Storage

Note that there *is no backend storage*. This widget offers no way to save your text and view it on another computer. There is no registering, no signing in. However, it does save locally to your browser. At the time I wrote this, I was exclusively a frontend developer, and creating a backend service for persisting the data was beyond my abilities.

### Not Maintained

I wrote this in 2019. Unless I change this README file, you should consider this project **no longer maintained**. I keep it more as a portfolio example. I hope a potential employer will bear the year of writing in mind when reviewing the code.

## Technology

Headline: this is a React/Redux project.

I don't remember building this project very clearly, but I'm fairly sure I used create-react-app and then ejected it. This would explain why there are so many dev dependencies in the general "dependencies" section of my package.json file.

I used Redux to create a global state container, as was the style at the time. 

## ScripDraft-Angular

Consider also https://github.com/xerocross/scripdraft-angular, an almost identical app I wrote later using Angular 2+ in Typescript.

## Retrospect in 2023

I'm reviewing this project now, in June 2023. I wrote it originally in 2019. I used the packages and React idioms of the time. Inspecting the code now, I am happy to see that at least I can install the project and run it locally for development, even on an up-to-date Node version. I see things that I could improve, but maintaining my old widgets is not a high priority.

If I do decide to update this widget, most likely I will create a fresh React app and add all necessary packages up-to-date, then just port my code files over as-is as much as possible.