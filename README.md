**TodoMVC jQuery**

URL: https://hyperdev.com/#!/project/maze-stealer

This is the workspace for the watchandcode.com
screencast series on the jQuery version of TodoMVC.

**How to Read Source Code**

Before you start

1. Read the docs (if they exist).
2. Run the code.
3. Play with the app to see what the code is supposed to do.
4. Think about how the code might be implemented.
5. Get the code into an editor.

The process

1. Look at the file structure.
2. Get a sense for the vocabulary.
3. Keep a note of unfamiliar concepts that you'll need to research later.
4. Do a quick read-through without diving into concepts from #3.
5. Test one feature with the debugger.
6. Document and add comments to confusing areas.
7. Research items in #3 only if required.
8. Repeat.

Next level

1. Replicate parts of the app by hand (in the console).
2. Make small changes and see what happens.
3. Add a new feature.

Unfamiliar concepts

1. jQuery.
2. What is the role of base.js?
3. What is the role of director.js
4. Handlebars.
5. uuid
6. localStorage.
7. JSON.

## todoMVC-jQuery

Useful links

https://github.com/tastejs/todomvc/blob/master/app-spec.md

### Notes

start with things that are the most elemental or essential to the app. start looking there. for the todo list app it might be add a new todo and then delete it.

- other .js and .css dependencies
     disable each and see what fails.
- base.js
- director.js
- `this` with and without bind.
- Method chaining.

### Get all object methods
```
var appObjects = Object.keys(App);
console.log('\n', appObjects);
```
- Handlebars
- Router, Routing director.js
- splice()
- bind() and 'this'
- event listeners / handlers


## Util
- uuid
- pluralize
- localStorage


## App
- init
- bindEvents
- render
- renderFooter
- toggleAll
- getActiveTodos
- getCompletedTodos
- getFilteredTodos
- destroyCompleted
- indexFromEl
- create
- toggle
- edit
- editKeyup
- update
- destroy


