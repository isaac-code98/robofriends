# Logic Notes:

## General:

- React manages to make the website, the DOM change in predictable ways in easy ways to scale as well as manage.
- React can be used in mobile native apps, VR, desktop apps.
- React is component based.
- Data flows from top to bottom, and never the other way around.
- If the parent components change, only their children know about the change, the parents don't really care about the change since the data flow is downstream.
- Virtual DOM: With react we have a react bot and it creates the v-dom, which is just a javascript object, that just describes the website and current state, we just give the object to the React, and the bot will autotimaclly make changes to the dom and paint the picture in the most optimal way possible.
- src folder contains the logic
- first thing when you load that is the index.js
- class components need to extend React.Component and then render/return them
- tachyons similar to boostrapped css
- jsx allows you to write this html-like syntax in your javascript
- not actual html tags jsx creates their own virtual/fake dom, then looks at vdom and real dom and say this part has changed, now im going to change the dom now based off the vdom

## Classes vs Hooks

- one of newer ways to write components is using hooks, fairly new, very specific to react,
- start off with classes and then move to hooks
-

## Installation:

- npx comes out of the box for you, it's a package runner, allows us to run it globally without explicitly stating it
- npx create-react-app my-app
- cd my-app
- npm start
