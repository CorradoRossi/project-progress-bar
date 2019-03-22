## Project Progress Bar

A visual report of how far along I am in certain projects.

Fun fact: Nested emmet statements like this save me untold amounts of tedious and repetetive copy pasting. 

```
ul.project-list#project-list>(li.project.project-website*20>h3+progress.project-progress[max="100" value="0"]>strong{Progress: 0%})
```

That creates an unordered list with a class name and an id with 20 list items with class names, with progress tag with a max and value custom tags followed by a strong tag that says progress: 0%. Copy pasting that would be much more of a PITA than writing an emmet string, and once you get quick with them they're remarkably powerful.