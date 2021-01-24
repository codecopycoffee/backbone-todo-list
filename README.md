# backbone-todo-list
Single file To Do list application using Backbone.js 
<br>Challenges:
* Working with Backbone for the first time
* I added strikethrough to the text of completed items. Originally I did this with toggleClass() in the completed() function, but the strikethrough would disappear when switching filters or refreshing because it wasn't part of the completed "state", so I fixed that
* At one point I got a TypeError and discovered that changing a regular object into a jQuery object is as easy as surrounding it with $().

Preview:

<img src="https://github.com/codecopycoffee/backbone-todo-list/blob/main/todo-preview.png" alt="to do list preview image">
