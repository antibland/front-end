# Group Projects

## Build a Practical Layout

Constructing a three column layout was once a bit of a pain. Now, with flexbox, that's no longer the case. Often referred to as the "holy grail" of web layouts, build a three column layout with a header and footer. Search engines reward developers who use semantic elements in their markup, so let's use elements like `<header>`, `<footer>`, `<nav>`, `<main>` and `<aside>`.

When you're done, your layout should look similar to this:

<img src='https://dl.dropboxusercontent.com/u/24799515/holy_grail.png' alt='' width='600' />

**Project file(s)**

https://github.com/antibland/front-end/tree/gh-pages/group_projects/questions/0

**Extra Credit**

Three columns looks pretty bad on a phone. When the screen is 600 pixels and below, add a `@media query` so that your layout stacks appropriately.

<img src='https://dl.dropboxusercontent.com/u/24799515/mobile.png' alt='' width='500' />

## Click Event Handlers

We have three boxes and need to make them respond to user clicks. When a user clicks a box, alert the user that the particular box was clicked. To access the text in the box, use `innerHTML`. For example, if the second box was clicked, the user should be alerted something like, "You clicked box 2".

**Project file(s)**

https://github.com/antibland/front-end/tree/gh-pages/group_projects/questions/1

**Extra Credit**

When the user clicks on a box, *before the alert*, first prompt her for her name. If no name is provided, keep prompting until a name is provided. Once you've got a name, alert the user something like, "Hi Janice. You clicked box 2".

## Run a Function Once

Users of our website are writing us to complain about a new popup feature we introduced. They're willing to see it once, but not every time they visit the website. Using `localStorage`, ensure that the `showPopup` function is only shown one time. Reloading the page should print nothing to the console.

**Removing a `localStorage` key from the console.**

If you need to remove a previously set storage key, open up developer tools and click the 'Resources' tab. Open the 'LocalStorage' folder and delete the key you wish to remove.

<img src='https://dl.dropboxusercontent.com/u/24799515/remove_storage.png' alt='' width='500' />

**Project file(s)**

https://github.com/antibland/front-end/tree/gh-pages/group_projects/questions/2

## Trading Places

Animations and transitions don't have a native awareness of when one another ends. However, animations and transitions can detect when they themselves have completed through the JavaScript events `animationend` and `transitionend`.

Your mission is to swap the position of the two balls on the screen. When the red ball animates to the position of black ball, move the black ball to the original position of the red ball.

<img src='https://dl.dropboxusercontent.com/u/24799515/trade_paces.gif' alt='' width='500' />

**Project file(s)**

https://github.com/antibland/front-end/tree/gh-pages/group_projects/questions/3

**Extra Credit**

In addition to swapping the position of the two balls, also swap their color.
